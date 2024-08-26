
<!--  Big O Notation
Space Complexity O(n): The function creates an array fib that stores all Fibonacci numbers up to the nth element, so the space required grows linearly with 𝑛 .
 -->


# fib

# The Fibonacci sequence is a sequence in which each number is the sum of the two preceding ones. //  Exp. 01123581321


# The difference in the loop and recursion model

# Although they both repeat things in a program  ,they do it difference ways 

# Loops  Use Control Variables but sometimes use other boolean events to eventually stop the process.

#  Common loops - while - do while -for

# A Loop is memory efficient. vs  recursion is Memory costly.

# Anything done by a loop can be done by recursion however everthing done by recursion cant be done by loop

# exp  for (let x = 0; x < 5; x++) {console.log(x);} - Loop


# exp  function doStuff(x) {if (x > 0) {doStuff(x - 1);} console.log(x);}  doStuff(4); - Recursion


# A loop would have great difficult performing a traverse while recursion can do it easily 

# Recursion Define a Method that call Itself  using a if else statement 


# Summary they are both use to repeat a  process sometimes loops might not work use a recursion.


