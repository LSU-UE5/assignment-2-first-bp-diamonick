# Assignment #2 - First Blueprint

Diamonick Dunn

This is my submission for Assignment #2.

## Description
* All variables ae private.

* <b>Assignment_2A</b>
  * BP_Clock is a blueprint that displays the current time of day in hours:minutes:seconds.
  * Sample Format: 11:50:06
  * I made a custom function called "Time Format Text (Int)". 
    * <b>Input:</b> (Int) Value
    * <b>Output:</b> (Text) Output Text
    * <b>Description:</b> This function takes an integer and formats the value to pad single digit numbers. Before it formats the text, it checks to see if the value is less than 10. If true, write it as it is. Otherwise, add a "0" before the value. It outputs the newly formatted text.
    * I used this function to format the hours, minutes, and seconds.
  * I used the GetHour12 action in the blueprint.


* <b>Assignment_2B</b>
  * BP_Guess_Number is a blueprint that displays a random number from 1 to 20 and another number that starts at 0.
  * Press the spacebar to increment the guessing number by 1.
  * Once the number you are guessing matches with the displayed number, a "You Win!" message will pop up. After 2 seconds, the game will restart (and by restart, I mean resetting the random number and setting your guess number to 0).
  
