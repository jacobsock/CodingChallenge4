
#Coding Challenge 4: Introducing Functions

Objective: This exercise will teach you how to encapsulate code into functions by refactoring the code from Coding Challenge 3 to use functions. This will help you understand the concept of reusability and modularity in Swift programming.

Step 1: Copy Over Coding Challenge Solution 3 to a new Swift file in a separate repository named "Coding Challenge Solution 4".

Step 2: Refactor the following features from Coding Challenge 3 to use functions in your new file:

Part 1: Handling User Reviews
Create a Function for Calculating Average Rating:

Create a function named calculateAverageRating that takes an array of Double (user reviews) as a parameter and returns a Double (average rating).
Move the logic for calculating the average rating from the for loop to this function.
Call this function in the main part of your code and print the returned average rating with descriptive text.
Create a Function for Counting Reviews by Rating Category:

Create a function named countReviewsByCategory that takes an array of Double (user reviews) as a parameter and returns a tuple containing four Int values (counts of Excellent, Good, Average, and Poor reviews).
Move the logic for counting reviews by category from the for loop to this function.
Call this function in the main part of your code and print the counts of reviews in each category with descriptive text.

---------------------------------------------

Challenge Tasks:

Test Your Functions:

Add more test cases by creating different arrays of user reviews and passing them to your functions.
Print the results to verify the correctness of your functions.
Enhance Your Functions (Optional):

Modify the calculateAverageRating function to handle the case where the array of reviews is empty.
Modify the countReviewsByCategory function to also return the percentage of reviews in each category.
This challenge will help you understand how to create and use functions, making your code more organized, readable, and reusable.
