# JAVA

## CHALLENGE 1

Welcome to the world of Java! In this challenge, we practice printing to stdout.

The code stubs in your editor declare a Solution class and a main method. Complete the main method by copying the two lines of code below and pasting them inside the body of your main method.

        System.out.println("Hello, World.");
        System.out.println("Hello, Java.");

Input Format

There is no input for this challenge.

Output Format

You must print two lines of output:

Print Hello, World. on the first line.
Print Hello, Java. on the second line.
Sample Output

Hello, World.
Hello, Java.

## CHALLENGE 2



## CHALLENGE 3

Given an integer, N, perform the following conditional actions:

If N is odd, print Weird
If N is even and in the inclusive range of 2 to 5, print Not Weird
If N is even and in the inclusive range of 6 to 20, print Weird
If N is even and greater than 20, print Not Weird

Complete the stub code provided in your editor to print whether or not  is weird.

Input Format

A single line containing a positive integer, N.

Constraints

Output Format

Print Weird if the number is weird; otherwise, print Not Weird.

Sample Input 0

        3

Sample Output 0

Weird
Sample Input 1

        24

Sample Output 1

Not Weird

## CHALLENGE 4

In this challenge, you must read an integer, a double, and a String from stdin, then print the values according to the instructions in the Output Format section below. To make the problem a little easier, a portion of the code is provided for you in the editor.

Note: We recommend completing Java Stdin and Stdout I before attempting this challenge.

Input Format

There are three lines of input:

The first line contains an integer.
The second line contains a double.
The third line contains a String.
Output Format

There are three lines of output:

On the first line, print String: followed by the unaltered String read from stdin.
On the second line, print Double: followed by the unaltered double read from stdin.
On the third line, print Int: followed by the unaltered integer read from stdin.
To make the problem easier, a portion of the code is already provided in the editor.

Note: If you use the nextLine() method immediately following the nextInt() method, recall that nextInt() reads integer tokens; because of this, the last newline character for that line of integer input is still queued in the input buffer and the next nextLine() will be reading the remainder of the integer line (which is empty).

Sample Input

        42

        3.1415

        Welcome to HackerRank's Java tutorials!

Sample Output

        String: Welcome to HackerRank's Java tutorials!

        Double: 3.1415

        Int: 42
