# Javascript-Algorithms-Free-Code-Camp-


FreeCodeCamp has javascript algorithims that I have completed in order to show competency and gain certificates. 
Below are the questions of the assignment and their solutions posted by the same name in the repository.  
*************************************************************************************

REVERSE A STRING

Reverse the provided string.

You may need to turn the string into an array before you can reverse it.

Your result must be a string.

**************************************************************************************

FACTORIALIZE A NUMBER

Return the factorial of the provided integer.

If the integer is represented with the letter n, a factorial is the product of all positive integers less than or equal to n.

Factorials are often represented with the shorthand notation n!

For example: 5! = 1 * 2 * 3 * 4 * 5 = 120

***************************************************************************************

CHECK FOR PALINDROMES

Return true if the given string is a palindrome. Otherwise, return false.

A palindrome is a word or sentence that's spelled the same way both forward and backward, ignoring punctuation, case, and spacing.

Note
You'll need to remove all non-alphanumeric characters (punctuation, spaces and symbols) and turn everything lower case in order to check for palindromes.

We'll pass strings with varying formats, such as "racecar", "RaceCar", and "race CAR" among others.

We'll also pass strings with special symbols, such as "2A3*3a2", "2A3 3a2", and "2_A3*3#A2".

***************************************************************************************

FIND THE LONGEST WORD IN A STRING

Return the length of the longest word in the provided sentence.

Your response should be a number.

***************************************************************************************

TITLE CASE IN A SENTENCE

Return the provided string with the first letter of each word capitalized. Make sure the rest of the word is in lower case.

For the purpose of this exercise, you should also capitalize connecting words like "the" and "of".

**************************************************************************************

RETURN LARGEST NUMBERS IN ARRAY

function largestOfFour(arr) {
  
  var results = [];
  
  for (var n = 0; n < arr.length; n++) {
    var largestNumber = 0;
  
    for (var sb = 0; sb < arr[n].length; sb++) {
      if (arr[n][sb] > largestNumber) {
        largestNumber = arr[n][sb];
      }
    
    }
    results[n] = largestNumber;
  }

  return results;
}

largestOfFour([[4, 5, 1, 3], [13, 27, 18, 26], [32, 35, 37, 39], [1000, 1001, 857, 1]]);

****************************************************************************************
