# Class 08 - Operators and Loops

In JavaScript, an expression is any valid block of code that results in a value. For example, 
                console.log(1 === 1) 
would produce the boolean value _true_.

Loops are used in JavaScript are used to perform an action repeatedly. An example of this would be the following:

                for(let i = 1; i <= 10; i++ ){
                    console.log(5 * i);
                }

This block of code would log the first 10 numbers of the 5 times table, ending at 5 x 10 as _i_ would be equal to 10 and the condition for the loop to end would be met. 

Another common form of loop in JavaScript is the _while_ loop which executes until a condition defined when the statement is created is met, for example: 

                let i = 1;
                while(i <= 10){
                    console.log(5 * i);
                    i++;
                }