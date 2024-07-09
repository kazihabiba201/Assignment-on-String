// Task 1:


// Write a function that does the following task.
// You are given a string s and an integer array indices of the same length. The string s will be shuffled such that the character at the ith position moves to indices[i] in the shuffled string. Return the shuffled string.
// Also, mention the Time and Space Complexity of your solution

// Constraints:

// s.length == indices.length == n
// 1 <= n <= 100
// s consists of only lowercase English letters.
// 0 <= indices[i] < n
// All values of indices are unique.


// Example 1:

// Input: s = "mamacode", indices = [4,5,6,7,0,1,2,3]
// Output: "codemama"
// Explanation: As shown, "mamacode" becomes "codemama" after shuffling.

// Example 2:

// Input: s = "dosta", indices = [4,0,1,2,3]
// Output: "ostad"
// Explanation: After shuffling, each character remains in its position.


// Example 3:

// Input: s = "abc", indices = [1,0,2]
// Output: "bac"
// Explanation: After shuffling, each character remains in its position

Solution:

/**
 * @param {string} s - The input string to be shuffled.
 * @param {number[]} indices - Array indicating the new positions of each character.
 * @return {string} - The shuffled string.
 */
function restoreString(s, indices) {

    let shuffled = new Array(s.length);
    
    // Iterate through each character in the string
    for (let i = 0; i < s.length; i++) {
       // Place each character at the new position
        shuffled[indices[i]] = s[i];
    }
    
    // Join the array into a string and return it
    return shuffled.join('');
}

function getUserInput() {
    // The string input
    let s = prompt("Enter the string:");
    
//The indices array input
    let inputOfIndices = prompt("Enter the indices array as comma-separated values:");
    let indices = inputOfIndices.split(',').map(Number);
    
    // Call the restoreString function with the inputs
    let result = restoreString(s, indices);
    
    // Display the result
    console.log(result);
}


getUserInput();

//Time Complexity: O(n)
//Space Complexity: O(n)
