Exercises
==========
1. *Encode and decode*
    1. Create two strings, one for a username and one for a password. Concatenate them together, separated by a colon. Use a method from the Groovy JDK to convert the resulting String to a byte array. Then use the `encodeBase64` method on byte array to create an encoded string.
    
    2. Decode the string by using the `decodeBase64` method, and using the result as an argument to the String constructor. Use the split method to return the original username and password.
    
2. *Sorting a list*

    Create a class called `Course`, with a `String` attribute called `name` and an `int` attribute called `days`. Create a list of four course instances, where at least two have the same number of days. Sort the list by number of days. Then, sort the list by days, but when the days are equal, sort by name.

3. *Operator overloading*
    1. Create a class called `Money` with a double `amount` and a `String` `currency` (like USD or EUR). Implement a `plus` method that checks that the currencies are the same and, if so, returns a new `Money` instance with the sum of the amounts and the correct currency. Write a similar `minus` method.
   
    2. Write a `MoneyTest` class in Groovy that uses + and - and verifies that they work properly.
    
