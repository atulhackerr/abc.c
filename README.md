# abc.c
C Code of Getting Age

This C code gets the age of the user and prints it out. It uses the stdio.h library to read the user's input and print the output.
C

#include <stdio.h>

int main() {
  // Declare a variable to store the user's age.
  int age;

  // Prompt the user to enter their age.
  printf("Enter your age: ");

  // Read the user's input into the `age` variable.
  scanf("%d", &age);

  // Print the user's age.
  printf("Your age is %d.\n", age);

  return 0;
}

Use code with caution. Learn more
How to Run the Code

To run the code, you will need to have a C compiler installed on your computer. Once you have a compiler, you can compile the code by running the following command:

gcc -o age age.c

This will create an executable file called age. You can then run the code by running the following command:

./age

This will prompt you to enter your age. Enter your age and press Enter. The code will then print your age.
Example Output

For example, if you enter the age 25, the code will print the following output:

Enter your age: 25
Your age is 25.

Conclusion

This is a simple C code that gets the age of the user and prints it out. You can use this code as a starting point to learn more about C programming.
