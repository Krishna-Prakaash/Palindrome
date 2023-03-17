# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## Step 1:
To start the C# program in visual Studio 2022.

## Step 2:
Create a class and declare two variable with string datatype.

## Step 3:
Loop over the entire string and reverse it.

## Step 4:
Use if condition to check whether the string and the reversed string is equal or not.

## Step 5:
print palindrome if it's equal else print not a palindrome.

## Step 6:
Save the program and run the program in visual studio 2022.
## Program:
DEVELOPED BY : KRISHNA PRAKAASH D M 


REG.NO : 212221230052
```
using System;
namespace PALINDROME
{
    public class Palindrome
    {
        static void Main(string[] args)
        {
            string word, reverse = "";
            word = Convert.ToString(Console.ReadLine());
            Console.WriteLine("before reverse:" + word);
            for (int i = word.Length - 1; i >= 0; i--)
            {
                reverse += word[i];
            }
            if (reverse == word)
            {
                Console.WriteLine("{0} it is palindrome", reverse);
            }
            else
            {
                Console.WriteLine("{0} its not palindrome", reverse);
            }
            Console.ReadLine();
        }
    }
}
```

## Output:
 NOT A PALINDROME
![OP-1](https://user-images.githubusercontent.com/93427144/225880173-fe31c9b1-c816-4ebc-8a5e-8da4ede70006.png)

PALINDROME:
![OP-2](https://user-images.githubusercontent.com/93427144/225880262-2979e0c8-c225-4889-9c1b-074ead6c5c79.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
