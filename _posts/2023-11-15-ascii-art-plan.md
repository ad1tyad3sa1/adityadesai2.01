---
toc: true
comments: false
layout: post
title: Ascii Art Blog
description: Ascii Art Binary Program Code and Updates
type: plans 
courses: { csp: {week: 1} }
---

# Initial Code for my Feature

```javascript

//Style for black canvas
<style>
   #asciiOutput {
    background-color: black;
    color: white;
   }
</style>

<!-- Input element for selecting an image file -->
<input type="file" id="imageInput" accept="image/*">

<!-- Placeholder for displaying the ASCII art -->
<pre id="asciiOutput"></pre>

<script>

    // Event listener for changes in the selected image file
    document.getElementById('imageInput').addEventListener('change', handleImage);

    // Function to handle the selected image file
    function handleImage() {
        const input = document.getElementById('imageInput');
        const output = document.getElementById('asciiOutput');

        // Create an Image object
        const img = new Image();

        // Event handler when the image is loaded
        img.onload = function() {
            // Generate ASCII art from the image
            const asciiArt = imageToAscii(img);

            // Display ASCII art in the output element
            output.innerHTML = asciiArt;
        };

        // Read the selected file as a data URL and set it as the source of the Image object
        const file = input.files[0];
        const reader = new FileReader();
        reader.onload = function(e) {
            img.src = e.target.result;
        };

        reader.readAsDataURL(file);
    }

    // Function to generate ASCII art from the image
    function imageToAscii(img) {
        // Create a temporary canvas and get its 2D rendering context
        const canvas = document.createElement('canvas');
        const ctx = canvas.getContext('2d');

        // Define the width for the ASCII output
        const outputWidth = 100;

        // Calculate the new width and height based on the original image dimensions
        const aspectRatio = img.width / img.height;
        const newWidth = Math.min(outputWidth, img.width);
        const newHeight = Math.floor(newWidth / aspectRatio);

        // Set the canvas dimensions
        canvas.width = newWidth;
        canvas.height = newHeight;

        // Draw the resized image on the canvas
        ctx.drawImage(img, 0, 0, newWidth, newHeight);

        // Get the pixel data from the canvas
        const imageData = ctx.getImageData(0, 0, newWidth, newHeight).data;

        // Initialize the string for storing ASCII art
        let asciiArt = '';

        // Process each pixel in the image
        for (let i = 0; i < imageData.length; i += 4) {
            // Convert RGB values to binary
            const binaryR = imageData[i].toString(2).padStart(8, '0');
            const binaryG = imageData[i + 1].toString(2).padStart(8, '0');
            const binaryB = imageData[i + 2].toString(2).padStart(8, '0');

            // Combine binary values to form a single binary string
            const binaryValue = binaryR + binaryG + binaryB;

            // Use specific criteria to determine background or foreground
            const char = isForeground(binaryValue) ? '*' : ' ';

            // Append the character to the ASCII art string
            asciiArt += char;

            // Add a line break at the end of each row
            if ((i / 4 + 1) % newWidth === 0) {
                asciiArt += '\n';
            }
        }

        // Return the generated ASCII art
        return asciiArt;
    }

    // Function to determine foreground based on binary value
    function isForeground(binaryValue) {
        // Add your criteria for determining foreground
        // For example, you can check if the binary value starts with '1'
        return binaryValue.startsWith('1');
    }
</script>

```

Key Points:

* Binary representation of bits in the image
* *Astrix* and _ for every bit creating the ascii art
* User can apply specific image into program

Possible Improvements:

* Work on sizing of the image to fit perfectly
* Implement black background to make ascii image look better
* Incorporating more elements into feature

Commits:

[Work on Program](https://github.com/trevorhuang1/cpt_warmup/commit/8d2ce0585463927361336e4c41df17ed84b469e7)

[Update on Canvas](https://github.com/trevorhuang1/cpt_warmup/commit/4d3509a5712ab6adcf702b442bc1e325e379a30a)