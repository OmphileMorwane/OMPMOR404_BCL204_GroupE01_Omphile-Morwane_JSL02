# [JSL02] Submission: Debug the DOM

## Overview

The objective of this project was to prevent the addition of duplicate goals to a list. It first fetches all exisitng goals from the list and iterates through them by using `querySelectorAll` function. For each existing goal, it compares its text content to the input goal. If a duplicate is found, it displays an alert message and terminates the function execution, ensuring that only unigue goals are added to the list.

## Reflections

### Areas of Mastery

**JavaScript Functionality**:
No mastery as yet, as this is still an introduction to Javascript, but I understood the execution of the project so well. It was a great practice of using the if else staments and also using the 'return' control flow statement which immediately stops the execution of the current function and returns control to the caaling code.

### Challenges Faced :

None so far.

### Areas for Improvement

Practice the whole course to get comfortable using Javascript.

## Overall Learning Experience and code choice.

I learned how to prevent the addition of duplicate goals to a list. To archieve that I firstly had to retrieve all existing goals from the list by using the loop 'querySelectorAll' function for existingGoals. Which is part of the DOM API that is used to select and retrieve elements from the DOM that matches the "li" CSS selector. This function returns a NodeList containing all elements that match the provider selector. The reason for this choice was so that the code can tell if a goal has already been added. Then inside the 'for loop', I created a condition that if a new input is the same as one of the existing goals, it can alert the user that the duplicate goal exists, and the 'return' keyword is used for the termination of the function when duplicates are found.
