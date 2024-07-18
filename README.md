Grammar Checker

This project demonstrates basic text processing using JavaScript. It focuses on filtering out unnecessary words, correcting misspelled words, and replacing inappropriate words in a given paragraph.

Getting Started:

1. Ensure you have Node.js installed on your machine. 
2. If not, download and install it from Node.js.
3. Clone this repository to your local machine.
4. Navigate to the project directory.
   
RUNNING THE CODE:
To run the code, execute the following command in your terminal:
---------------------------------------------------------------------
node grammarChecker.js
---------------------------------------------------------------------

CODE EXPLANATION:

The JavaScript code performs the following tasks:

1. Splits the given paragraph into an array of words: The .split(' ') method is used to separate the story string by spaces, storing each word as an element in the array.
2. Logs the original array of words: Displays the array of words for initial inspection.
3. Counts the number of words: Uses a forEach loop to count the total number of words in the paragraph.
4. Filters out an unnecessary word: The .filter() method removes all instances of the word 'literally'.
5. Corrects a misspelled word: The .map() method replaces 'beautifull' with 'beautiful'.
6. Finds and replaces an inappropriate word: The .findIndex() method locates the index of 'freaking' and replaces it with 'really'.
7. Checks if all words are 10 characters or less: The .every() method checks if all words meet this criterion and logs the result.
8. Replaces words longer than 10 characters: The .map() method replaces any word longer than 10 characters with 'stunning'.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

By following this README, you should have a clear understanding of the project's purpose and how to execute the code. If you encounter any issues, please refer to the Issues section for potential fixes.
