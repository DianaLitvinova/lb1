<h2> lb1 </h2>
<p align="center">
  <img src="Screenshots/1.png" alt="Описание изображения 2"/>
</p>

``` csharp
using System;

class Program
{
    static void Main()
    {
        Random random = new Random();

        Console.WriteLine("Enter the number of points:");
        int n = int.Parse(Console.ReadLine());

        double[,] cartesianCoords = new double[n, 2]; // x и y
```
