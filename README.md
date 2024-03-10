# Exp04-Jagged-Array
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.

## Algorithm:
### Step1:
Create a new Class named cpu.

### Step 2:
Create a jagged array of 4 arrays. int[][] array = new int[][];

### Step 3:
Create as many sub-nodes as you wish inside one node of jagged array.

### Step 4:
Give the sample CPU usage in the jagged array.

### Step 5:
Print the sample CPU usage in the jagged array.

### Step 6:
End the Program.

## Program:
```
using System;
public class Pattern
{
    public static void Main()
    {
      int[][] jaggedArray = new int[4][];
      jaggedArray[0] = new int[3];
      jaggedArray[1] = new int[5];
      jaggedArray[2] = new int[6];
      jaggedArray[3] = new int[4];
      for (int i = 0; i < jaggedArray.Length; i++)
      {
        for (int j = 0; j < jaggedArray[i].Length; j++)
        {
          jaggedArray[i][j] = i * j + 60;
          Console.WriteLine("CPU usage of {0} node is {1}%", i + 1, jaggedArray[i][j]);

        }
      }
    }
}
```

## Output:
![image](https://github.com/ShyamKumar-AI-DS/Exp04-Jagged-Array/assets/93427182/1aee69ce-02c2-4cca-ad56-3f3fe6b24bf2)


## Result:
Thus C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.

