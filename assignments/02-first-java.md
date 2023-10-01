# [Video Link](https://youtu.be/TAtrPoaJ7gc)

## Write Java programs for the following:

**1. Write a program to print whether a number is even or odd, also take
input.**  
Solution:   
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter a number: ");

    int n = myObj.nextInt();
    if (n % 2 == 0) {
        System.out.println("Even");
    } else {
        System.out.println("Odd");
    }
}

```


**2. Take name as input and print a greeting message for that name.**  
Solution:  
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter your name: ");

    String name = myObj.nextLine();
    System.out.println("Hello, "+name);
}
```

**3. Write a program to input principal, time, and rate (P, T, R) from the user and
find Simple Interest.**  
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter principal, rate and time: ");

    int P = myObj.nextInt();
    int R = myObj.nextInt();
    int T = myObj.nextInt();

    float I = (P * R * T) / 100;
    System.out.println("Simple Interest is "+I.toString());
}
```
**4. Take in two numbers and an operator ('+', '-', '*', '/') and calculate the value. (Use if conditions)**  
Solution:  
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter any two numbers and an arithmetic operator");

    int a = myObj.nextInt();
    int b = myObj.nextInt();
    String op = myObj.nextLine();
    float result;

    switch(op) {
        case "+":
                  result = a + b;
                  System.out.println("Addition: "+result);
                  break;
        case "-":
                  result = a - b;
                  System.out.println("Subtraction: "+result);
                  break;
        case "/":
                  result = a / b;
                  System.out.println("Division: "+result);
                  break;
        case "*":
                  result = a * b;
                  System.out.println("Multiplication: "+result);
                  break;
        default:
                  System.out.println("Invalid Operator!!!");         
    }
}
```

**5. Take 2 numbers as input and print the largest number.**  
Solution:  
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter two numbers: ");

    int a = myObj.nextInt();
    int b = myObj.nextInt();
    int max = (a>b)?a:b;
    System.out.println("Largest: "+max);
}
```

**6. Input currency in rupees and output in USD.** 
Solution:  
```
public static void main (String [] args) {
    Scanner myObj = new Scanner(System.in);
    System.out.println("Enter amount in rupees: ");

    double inINR = myObj.nextLong();
    double oneUSDinINR = 83.04;

    double inUSD = inINR / oneUSDinINR;

    System.out.println("INR Equivalent in USD: "+inUSD);
}
```

**7. To calculate Fibonacci Series up to n numbers.**  
Solution:  
```
```
**8. To find out whether the given String is Palindrome or not.**  
**9. To find Armstrong Number between two given number.**  

