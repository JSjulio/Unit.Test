<!-- 
todo                                    Notes

? Test Formats 


*Unit test specifications should take the form of:

Expect [action] to be [some result]

    Example: For the prompt "A function called "addition" that returns the sum of two input integers", your tests might include:
        Expect addition(2, 3) to be a number
        Expect addition(2, 3) to be equal to 5
        Expect addition("a", 3) to be an error 
        

*Functional Test: 

When a user [does something with some parameters], [some thing should happen]

    Example: For the prompt was "A login and signup page that allows Single Sign-On with Google", your tests might include:
        When a user clicks "Log In" without filling in any information, they should be shown an error and prompted to sign up if they have not yet.
        When a user clicks "Log In" but has filled out an incorrect login or password, they should be shown an error and prompted to sign up if they have not yet.
    

? Task: 

For each prompt below: 

1. Read the prompt.
2. Identify the expectations.
3. Write specifications in pseudocode/plain English for all the tests that would be useful for that prompt.
4. Try to take any "edge cases," or unexpected circumstances, into account, and write test specs for them.
    P.S : Try not to write extraneous tests
---------------------------------------------------------------------------------------------------------------
todo                                    Assignment



? Unit Test: 

1. A function called "multiplication" that returns the product of the two input numbers.

    Expect multiplyNumbers(a, b) to be a number
    Expect multiplyNumbers(a, b) to be a positive or negative number 
    Expect multiplyNumbers(a, b) to be a whole number or an integer 
    Expect multiplyNumbers(3, 2) to be 6
    Expect multiplyNumbers(.5, 4) to 2
    Expect multiplyNumbers(a, 10) to be an error 


2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

            Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
            ...should result in [-1, 1, 3, 9, 15]
    
    Happy Paths: 
    Expect contactOdds([1, 2, 3, ], [8,-9, 10 ]) should result in [1, 3, -9]
    Expect contactOdds([1, 2, 3, ], [3, -9, 1 ]) to result in [1, 3, -9]

    Unhappy Path
    Expect contactOdds([a, b, c, ], [h, i, j ]) 'Only numbers please!'  
    Expect contactOdds([],[]) to result in 'Please input two array of numbers!' 
    Expect contactOdds([!, 2, #, ], [-, 1, 17 ]) to result in 'Only numbers please!'     
    


? Functional Test: 

1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.


Happy Path 
When a user [Opens the webpage to shop], [a prompt pops up directing them to sign up by logging in with gmail, facebook, creating an account with their email/phone number, or continue as guest]
When a user [ logs in with gmail or facebook] [a prompt pops up asking them if they would like to save their credientials]
When a user [with saved credientials opens the shopping site] [their saved email and password credientials populate in the input locations]
When a user [signs up with an email or phone number], [they get a confirmation to their email / phone number]
When a user [succsessfully logs in with any method] [they will be redirected to the initial webpage they visited and allowed to add items to their car]
When a user [select an item from the broad Webpage of items] [they are brough to another webpage that has more specification about that item]
When a user [selects the item on it's specified webpage] [the cart emblem on the top right shows a number that correlates with the number of items in the cart]
When a user [selects the item on it's specified webpage] [a pop up comes directing them to keep shopping or checkout]
When a user [selects keep shopping after adding an item to their cart] [they are redirected to the page they were on before navigating to an item's specified page]
When a user [selects checkout] [They are directed to a page that ask them if they want to make an account or gives them the option to continue as a guest]
When a user [continues in the checkout] [they are brough to a summary page that shows all items they added to their cart and the amount of each items]
When a user [navigtes to the checkout page] [they are given the option to delete selected items from their cart before continuing to payment]
When a user [confirms their order on the order summary page] [they are directed to the checkout page and instructed to use a payment method]
When a user [inputs a valid payment method and confirms their purchase] [They are brought to a page that shows the total cost of the item including shipping and taxes]
When a user [confirms their order after seeing the total cost] [a pop up window appears saying their order was successfully purchased and a summary has been sent to their email/number]
When a user [without an account purchases an item as a guest] [a pop up appears requesting an email where the user wants the reciept sent to ]




Unhappy Path
When a user [enters the incorrect combination or email / password] [a pink banner will appear under the password box saying 'Incorrect email or password]
When a user [enters the incorrect combination or email / password] [a hypertext word saying 'Forgot Passowrd' will appear under the pink banner]
When a user [selects 'Forgot my password'] [They will be directed to enter their email in order to retrieve a key that will be sent for authentication]
When a user [enters the incorrect combination of email/password 5 times while having a valid email] [A message saying 'Your account has been locked' will appear 
When a user [enters the incorrect combination or email / password] [a red banner will appear under the password box saying 'Incorrect email or password]
When a user [inputs a invalid payment method] [a red banner appears on the page instructing the user to input a valid combination of payment information]
When a user [fails to input information into entries with "*" next to them] [They page reloads and highlights the entry the user did not fulfil and a banner pops up requesting the user to fill out the information]




    -->