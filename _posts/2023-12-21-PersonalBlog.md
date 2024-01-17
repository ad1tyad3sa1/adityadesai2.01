---
toc: true
comments: false
layout: base
title: Personal Blog
description: College Board Corrections and Self Reflection
type: plans
courses: { csp: {week: 5} }
---

# Learnings from Team Teach Topics

## Understanding Internet Routing:

Internet routing is like the invisible guide that ensures our digital data reaches its destination smoothly. It's crucial to appreciate the complexity behind our online experiences and understand the pathways that enable seamless connectivity.

Key Takeaway: Grasping internet routing helps us comprehend the backbone of the digital world, making us more informed users and contributors to the online space.

-------------------------------------------------------------------------------------------------
## Digital Divide: 

The digital divide underscores the disparities in internet access, emphasizing the need for inclusivity. Bridging this gap ensures that everyone, regardless of their background, has equal opportunities for education, employment, and social interaction.

Key Takeaway: Addressing the digital divide is a collective responsibility, and it is essential for creating a more equitable and connected global society.

-------------------------------------------------------------------------------------------------
## Beneficial and Harmful Effects of Technology:

While technology offers immense benefits, it also introduces challenges. Striking a balance between embracing innovation and mitigating the negative consequences is crucial for harnessing the positive potential of technology while minimizing its adverse impacts.

Key Takeaway: Achieving a harmonious relationship with technology requires conscious efforts to manage its effects and promote responsible usage.

-------------------------------------------------------------------------------------------------
## Crowdsourcing:

Crowdsourcing empowers collective problem-solving and creativity. It is important to recognize its potential while ensuring ethical practices, fair compensation, and the avoidance of exploitation in leveraging the collective intelligence of diverse groups.

Key Takeaway: Harnessing the power of the crowd can lead to innovative solutions, but it is imperative to approach it with ethical considerations at the forefront.

-------------------------------------------------------------------------------------------------
## Undecided Problems:

Embracing uncertainty and fostering interdisciplinary collaboration are essential in addressing ongoing and emerging global challenges. Certain problems can't be fixed and their exists no algorithms that can solve them.

Key Takeaway: Recognizing and accepting the existence of undecided problems and ways to work around them.

-------------------------------------------------------------------------------------------------
## Bias in Programs:

Algorithms wield considerable influence in our digital lives. Acknowledging and addressing biases in these algorithms are critical to ensuring fair and equitable outcomes, preventing inadvertent discrimination or exclusion.

Key Takeaway: Algorithmic transparency and ethical considerations are necessary to create a digital landscape that reflects the diversity and values of its users.

-------------------------------------------------------------------------------------------------
## Legal and Ethical Concerns:

Operating within legal and ethical frameworks is paramount in the digital realm. Questions surrounding data privacy, online surveillance, and the ethical use of technology highlight the importance of aligning our digital evolution with societal values.

Key Takeaway: Balancing innovation with responsibility ensures that our digital journey respects ethical standards and legal boundaries.

-------------------------------------------------------------------------------------------------
## Safe Computing: 

Safe computing practices, encompassing cybersecurity awareness and responsible online behavior, empower individuals to navigate the digital landscape securely. This is crucial for fostering a safer online environment for everyone.

Key Takeaway: Education and awareness are key components in creating a digital space where users feel confident, secure, and in control of their online experiences.

# Journey

## Takeaways from CPT Project

- Conduct a detailed analysis of project requirements and needs before starting the development process.

- Initial planning and development should be more thought out (ideation phase)

- Constant updating and adaption of plans while developing programs

- Identify potential risks early in the development process and develop strategies to mitigate them.

- Programming in parts and in a more organized way

- Segmenting code in smaller commits

- Organizing code so that it is easier for viewers to understand

- Add more descriptive comments regarding what your code does and how it works

- Gather feedback from potential users during the development process to make iterative improvements

- Regularly conduct code reviews with team members to ensure code quality, identify potential issues, and share knowledge

- Working more collaboratively with peers to make a more synchronized project

- Work on presentation of project referring to standards set by College Board (no mouse scrolling)

# Test Corrections/Discovery

-------------------------------------------------------------------------------------------------
## Question 7

![Question 7](https://files.catbox.moe/ns81il.png)

Answer/Explanation: I likely made this mistake by misreading the problem and not realizing exactly what it was asking. Now the answer seems more apparent after reading the solution. 

-------------------------------------------------------------------------------------------------
## Question 15

![Question 15](https://files.catbox.moe/m33rps.png)

Answer/Explanation: Conceptual error, interchanging the display block with the operation of adding 1 will keep the number of values outputted the same but each value will be 1 greater in Program B. Program B would output numbers 2-11 while A would produce numbers 1-10. Therefore the answer choice "Program A and program B display the same number of values, but the values differ" is correct over Program A and program B display identical values.

-------------------------------------------------------------------------------------------------
## Question 21

![Question 21](https://files.catbox.moe/4aivnj.png)

Answer/Explanation: Rereading problem and answer, it is clear I choice the wrong selection, I suppose that I was confused by the wording of each answer and now understand my mistake. 

-------------------------------------------------------------------------------------------------
## Question 37

![Question 37](https://files.catbox.moe/177zj8.png)

Answer/Explanation: The order of the parameters matter in the code, my answer choice skips the first iteration, the line between the points 
(2,6) and (8,8).

-------------------------------------------------------------------------------------------------
## Question 39

![Question 39](https://files.catbox.moe/2oto7p.png)

Answer/Explanation:  The program does not include the first element of the list in the sum because i is incremented before nums[i] is added to sum. By interchanging these two lines of code, the program will include all of the first ten elements of the list when computing the sum. Additionally, my answer choice was wrong because the program already iterates through first 10 terms.

-------------------------------------------------------------------------------------------------
## Question 42

![Question 42](https://files.catbox.moe/lnm5k9.png)

Answer/Explanation: Option D contains a Boolean expression is true if and only if score is between target - 10 and target + 10, inclusive. Therefore, it evaluates to true if and only if score is in the desired range. My answer choice in the first parameter had a flaw allowing the difference to be greater than 10.

-------------------------------------------------------------------------------------------------
## Question 50

![Question 50](https://files.catbox.moe/wu3gfn.png)

Answer/Explanation: For an algorithm to run in reasonable time, it must take a number of steps less than or equal to a polynomial function. Algorithm I accesses elements times (twice for each of n elements), which is considered reasonable time. Algorithm II accesses elements (n times for each of n elements), which is considered reasonable time. Algorithm III accesses 10 elements, which is considered reasonable time. Therefore all algorithms ran with reasonable time.  

-------------------------------------------------------------------------------------------------
## Question 56

![Question 56](https://files.catbox.moe/frhn8e.png)

Answer/Explanation: Correct. Version I calls the GetPrediction procedure once for each element of idList, or four times total. Since each call requires 1 minute of execution time, version I requires approximately 4 minutes to execute. Version II calls the GetPrediction procedure twice for each element of idList, and then again in the final display statement. This results in the procedure being called nine times, requiring approximately 9 minutes of execution time.

-------------------------------------------------------------------------------------------------
## Question 62

![Question 62](https://files.catbox.moe/knwxis.png)

Answer/Explanation: I selected the values that evaluated the function to false. I am not sure if I read the question wrong due to lack of concentration or just thought I was selecting the programs outputting false. It is obvious that I am wrong, the programs with OR gates as their parameter or operation will most likely output true if x is set to true and y to false. 

-------------------------------------------------------------------------------------------------
## Question 65

![Question 65](https://files.catbox.moe/nndfba.png)

Answer/Explanation: This question at first was hard for me to understand. However, realizing the order in concatenation of words to form jackalope helped me understand why the two correct answers. 

The one I selected that was correct stores the substring "jack" in animal. It then concatenates "jack" and "a", storing the result "jacka" in animal. Lastly, it concatenates "jacka" and the substring "lope", storing the result "jackalope" in animal.

The other correct answer reversed this process, storing the substring "lope" in animal. It then concatenates "a" and "lope", storing the result "alope" in animal. Lastly, it concatenates the substring "jack" and "alope", storing the result "jackalope" in animal.