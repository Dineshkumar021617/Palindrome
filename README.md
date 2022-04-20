# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare two variable with string datatype

### Step3:
Loop over the entire string and reverse it

### Step4:
Use if condition to check whether the string and the reversed string is equal or not

### Step5:
print palindrome if it's equal else print not a palindrome.

### Step6:
stop
## Program:
```c#
using System;
class Palindrome
{
    static void Main()
    {
        string value, dupvalue, rev = "";
        value = Console.ReadLine();
        dupvalue = value;
        for (int s = value.Length - 1; s >= 0; s--)
        {
            rev += value[s];
        }
        if (rev == dupvalue)
            Console.WriteLine(dupvalue + " is a palindrome");
        else
            Console.WriteLine(dupvalue + " is not a palindrome");
    }
}
```
## Output:
![Screenshot (19)](https://user-images.githubusercontent.com/75234807/164180401-ce78ec0b-f248-466b-af79-540566fcb7a6.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
