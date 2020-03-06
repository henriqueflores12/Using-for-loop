# Using-for-loop
the counter and the array both start from 0(rather than 1).so within the loop
to select the current item from the array, e,g.,score[i].but remember that it is a number lower then you might expect (e,g.,first itaration is 0 second is 1)
a for loop is often used to loop through the items in an array
in this example, the score for each round of the test are stored in array called scores.

the total number of items in the array is stored in a variable called arrayLength. this number is obtained using the length property of the array.

there are three more varibles: roundNumber holds the round of the test; msg holds the message to display; i is the counter 
(declared outside the loop).

the loop starts with the for keyword then contains the condition inside the parentheses
as longs as the counter is less  than the total number of items 
in the array, the contents of the curly braces will continue to run.each time the loop runs the round number is increased by 1 inside the curly braces are rules that write the round number and the score to the msg variable. the variable declared outside of the loop are used within the loop

the msg variable is then written into the page it contains html so the innerHtml property is used to do this.
