SOFE4640U: Mobile Application Development, Assignment 1
Name: Sehaj Behl, Student ID: 100748987
	
 This assignment is about creating a mobile application that calculates your
 EMI (equated monthly installment) through mortgage details such as Mortgage principal amount, 
 Interest rate and amortization period. These details were fundamental in calculating the EMI. 
 Inside my source code, I structured my application to have 2 main activities, MainActivity and 
 EMI. These activities contain the logic for the calculation, as well as the intents used to navigate
 both activities. Firstly, I made three fields for the corresponding mortgage details, and a button for
 calculating the emi. I ensured that the mortgage principal and interest rate are double data types for 
 entering in decimals, and the amortization period is an integer for entering years. The EMI function 
 then calls the calculation function which contains the calculation logic. Additionally, an intent 
 is made that directs the screen to the EMI activity upon clicking the “Calculate my payments”
 button. The putExtra function is used on the intent to transfer the result of the calculation to the 
 different screen, a name “emiResult” holds the string value of the emi result. A calculation method was 
 made which plugs in the values from the input fields into the formula and returns the result. As an
 additional measure, I enclosed the EMI function into a try and catch block, so that if users don’t 
 enter all the required fields, the application throws a message at the user stating they must fill in 
 all the fields. On the EMI activity screen, the result is displayed in a textView component through 
 retrieving the result by the result that was stored in the “emuResult” name. There is also a back 
 button on the EMI activity screen to go back to the MainActivity page to enter mortgage details and recalculate. 
