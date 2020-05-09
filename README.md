# Hackerrank30DaysCode
This file contains all the solution which are submitted by me for Java labguage.
Task
To complete this challenge, you must save a line of input from stdin to a variable, print Hello, World. on a single line, and finally print the value of your variable on a second line.

You've got this!

Note: The instructions are Java-based, but we support submissions in many popular languages. You can switch languages using the drop-down menu above your editor, and the  variable may be written differently depending on the best-practice conventions of your submission language.

Input Format
Welcome to 30 Days of Code!

A single line of text denoting inputString (the variable whose contents must be printed).

Sample Output
Hello, World. 
Welcome to 30 Days of Code!


public class HelloWorld {
    public static void main(String[] args) {
        // Create a Scanner object to read input from stdin.
        Scanner scan = new Scanner(System.in); 
        
        // Read a full line of input from stdin and save it to our variable, inputString.
        String inputString = scan.nextLine(); 

        // Close the scanner object, because we've finished reading 
        // all of the input from stdin needed for this challenge.
        scan.close(); 
      
        // Print a string literal saying "Hello, World." to stdout.
        System.out.println("Hello, World.");
      System.out.println(inputString);
    }
}
