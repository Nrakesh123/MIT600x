HANGMAN PART 1: IS THE WORD GUESSED? : 5.0 POINTS
=================================================

Please read the Hangman Introduction before starting this problem. The helper functions you will be creating in the next three exercises are simply suggestions. If you'd prefer to structure your Hangman program in a different way, feel free to skip these exercises. However, if you're new to programming, or at a loss of how to construct this program, we strongly suggest that you implement the helper functions on this page before continuing on to Hangman Part 2.

We'll start by writing 3 simple functions that will help us easily code the Hangman problem. First, implement the function isWordGuessed that takes in two parameters - a string, secretWord, and a list of letters, lettersGuessed. This function returns a boolean - True if secretWord has been guessed (ie, all the letters of secretWord are in lettersGuessed) and False otherwise.

Example Usage:

    >>> secretWord = 'apple'
    >>> lettersGuessed = ['e', 'i', 'k', 'p', 'r', 's']
    >>> print isWordGuessed(secretWord, lettersGuessed)
    False

For this function, you may assume that all the letters in secretWord and lettersGuessed are lowercase.
