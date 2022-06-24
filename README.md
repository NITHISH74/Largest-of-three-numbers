# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers.


## Algorithm:
### Step 1:
To start the C# program in visual Studio 2022.
### Step 2:
Create a class and declare three variable with integer datatype.
### Step 3:
Use if condition to check whether Number1 is largest than number2 and number3.
### Step 4:
Use elif condition to check whether number2 is largest than number1 and number3
### Step 5:
Use else condition to display that third variable is largest among all the variables.
### Step 6:
Finish the C# program and run it.
### Step7:
To print the output for the largest of three numbers.
## Program:
```
using System;
public class hello
{
    public static void Main()
    {
        int num1, num2, num3;
        Console.WriteLine("Find the largest of three numbers:\n");

        Console.WriteLine("Enter the first number :");
        num1 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the second number :");
        num2 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the third number :");
        num3 = Convert.ToInt32(Console.ReadLine());

        if (num1 > num2)
        {
            if (num1 > num3)
            {
                Console.WriteLine("The first Number is the greatest among three"+num1);
            }
            else
            {
                Console.WriteLine("The third Number is the greatest among three"+num3);
            }
        }
        else if (num2 > num3)
            Console.WriteLine("The second Number is the greatest among three"+num2);
        else
            Console.WriteLine("The third Number is the greatest among three"+num3);
    }
}

```

## Output:
![image](https://user-images.githubusercontent.com/94164665/163829484-0e2f42ed-d146-44c6-9889-cf456cac78c5.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully.

