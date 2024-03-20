# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: 

Example 1 - Imperative:
https://www.loom.com/share/3f75972e7812433e921990a08c042bf0?sid=3bce0ec8-c8ba-444c-9f54-056fa80de3bf

Example 2 - Declarative:
https://www.loom.com/share/200cbc4240ee4337876a4863286ecb18?sid=b21875b0-c539-453f-92ca-74522c7af739

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyze these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Instructions

## Step 1: Clone the Repository

Repo Link: https://github.com/CodeSpace-Academy/Module_3_StudentNo_Classcode_Group_Name-Surname_JSL03

1. Access the provided repository containing the starter code and presentation template.
2. Clone the repository.
3. Open the cloned repository in your preferred code editor.

## Step 2: Analyze the Examples

1. In the cloned repository, you will find two JavaScript code examples labeled "Example 1" and "Example 2."
2. Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

## Step 3: Record Your Presentation

1. Use Loom (https://www.loom.com/).
2. Create a single video presentation for both examples that include the following:

   - Introduction of the example number.
   - Explanation of whether the example is imperative or declarative.
   - Detailed reasoning for your choice, discussing the code logic and style used in the example.
   - Mention any specific code structures or patterns that align with the chosen programming paradigm.
   
3. Keep each video presentation concise, with a maximum length of 2 minutes for each example. Your total recording time should not exceed 5 minutes.

## Step 4: Insert Loom Links

1. After recording, upload your presentation videos to Loom.
2. Obtain the Loom recording links for the video presentation.
3. Edit the `README.md` file in the cloned repository and insert the Loom recording links.
   
## Step 5: Submit Your Project
1. Commit your changes to the Git repository and push them to your GitHub account.
2. Ensure that the repository is public so that it can be accessed.
3. Submit the GitHub project link (URL) that includes your Loom recording link to the [JSL03] Project Tab on the LMS for evaluation.

# Project Evaluation

Your project will be evaluated based on your ability to:

- Accurately identify and differentiate between imperative and declarative programming styles.
- Provide clear and well-reasoned explanations for your choices.
- Present your findings concisely within the specified time limit.
- Follow the submission instructions accurately.

Follow the steps outlined above to complete the project successfully.

# Presentation Talking Points

Example #: 1

## Imperative Programming Paradigm Approach [2 Minutes]
1. **Step-by-Step Explanation:** Start by explaining the code logic in the imperative approach:
 - "give an authoritative command". Focuses on the HOW in coding, providing exact steps needed for a code solution. 
 - Explicitly defined grill Temp, followed by seasoning (that is defined but not used.)
 
   
Mention each step of the process in the code.   
Describe how the code provides explicit instructions for each action.
- Explicitly given a grill and steak Temp. In order to execute the code, the steak temp needs to change.
Discuss the use of variables to track the state and progress of the process.


2. **Emphasis on How:** Highlight how the imperative approach focuses on detailing "how" the task is accomplished.
Point out the use of loops, conditions, and explicit instructions.
- We never exit the while loop. Because we have specified the variable steakTemperature = 0, the condition of the while loop says while (steakTemperature < desiredDoneness), keep running. That will always be the case and we never move onto the If statement

Discuss any mutable variables or states that change during execution.
- mutable variable let grillTemperature = 204 is changed. The state remains unchanged because the mutable variable steakTemperature remains unchanged


Example #: 2

## Declarative Programming Paradigm Approach [2 Minutes]
1. **High-Level Process Description:** Explain the code logic in the declarative approach.
   - focuses on WHAT the program should accomplish.
   - Describe the cooking process in a high-level, abstract manner, using data-driven approach.
   - Emphasize that the code defines "what" should happen rather than "how" it should happen.

2. **Use of Data Structures:** Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
Explain how the process steps are organized in a structured format.
   - Array of objects that contain steps in a high-level manner (provides an overview of general steps without specific details to be carried out). This separates the actions from the implementation details, so we focus on what to do rather than how.
   - it says to preheat the grill to a certain temperature, but it doesn't detail the exact process of preheating.
   - Here if we chose to eliminate some of the 'cases' the code can still run.
Mention any abstraction layers or functions used to encapsulate actions.

# Learning Outcome [1 Minute]
Reflect on what you've learned from analyzing these code examples in different paradigms.
 - It was confusing because both examples had similarities. I was looking for explicit differences such as 'map, reduce, and filter', and example 1 is more readable (which is usually the case in Declarative programming)
