# N-ordle
A N-ordle game based on Wordle using Java
For Wordle
— There is a random word picked from a list of words
— We decided to make the maximum amount of guesses = 6 to reflect the real Wordle
— Enter a guess. The guess should consist of only letters and must be a certain length x. The game will not accept a guess with length less than x or greater than x.
— Do not use the caps lock key in any way, the guesses must be in lower case.
— If you press the caps lock key by accident then you must press it again because the game will not register capital letters.
— Do not press any other keys like numbers or shift.
— If you entered the wrong letter by mistake, use the backspace key to delete a letter at a time.
— The guess you enter must be an actual word or else the game will not accept it.
	(There are real five letter word guesses that may not be accepted because they are not in our word list)
— Upon entering a guess there will be green letters, yellow letters, and grey letters
	— Green: The letter is in the word and in the right spot
	— Yellow: The letter is in the word but in a different spot
	— Grey: The letter is not in the word
— If you get the correct word (all greens) in 6 or less tries you win. Else you lose
- It is a design choice that for a secret code of say OCEAN and a guess of say QUEEN, the first E would be green and the second one would be yellow instead of grey.

For Dordle
— The rules are the same as Wordle except you have 7 guesses instead of 6.
— In addition, a Dordle is two Wordles, each with their own secret code. You must get both secret codes correct in 7 or less tries. 
— It is a design choice that if you win one wordle before another you stop adding guesses to that wordle side.
