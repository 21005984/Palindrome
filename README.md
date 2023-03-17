# PALINDROME
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### step 1 :
Import the 'system' namespace to use the classes present in the "System namespace".

### step 2 :
Declare main method

### Step 3 :
Declare two string variables one is for getting the input and another is to reverse the input string.

### Step 4:

Using 'Console.Read' get the input from the user. 

### Step 5 :
using the for loop reverse the input string to check weather the input is palindrome or not.

### Step 6;
Print the result.

## Program:
~~~
using System;
namespace palindrom

{
    public class Program
    {
        static void Main(string[] arg)
        {
            string str1;
            string rev = "";
            Console.Write("Enter a string : ");
            str1 = Console.ReadLine();

            for (int i = str1.Length - 1; i >= 0; i--)
            {
                rev += str1[i];
            }
            if (str1 == rev)
            {
                Console.WriteLine("{0} is Palindrome.", str1);
            }
            else
            {
                Console.WriteLine("{0} is not a Palindrome.", str1);
            }
        }
    }
}
~~~

## Output:
![output](c3.jpeg)

![output](c4.jpeg)
## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
