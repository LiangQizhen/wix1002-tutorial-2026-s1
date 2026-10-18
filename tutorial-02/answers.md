# Tutorial 02 – Answers

## Question 1

### (a)

```java
System.out.print("Faculty of ");
System.out.print("Computer Science ");
System.out.print("and Information Technology");
System.out.println();
```

### (b)

```java
System.out.println("Faculty of\nComputer Science\nand Information Technology");
```

## Question 2

```java
System.out.println("\"SDN\" - Software-defined networking");
```

## Question 3

### (a)

```java
System.out.println("Java Programming");
```

### (b)

```java
System.out.println("Introduction to Java!");
```

### (c)

```java
// No error
System.out.println("\t is the horizontal tab character");
```

### (d)

```java
System.out.println("Java is case sensitive!");
```

## Question 4

### (a)

```java
String matricNumber;
```

### (b)

```java
double pi;
```

### (c)

```java
boolean M = false;
```

### (d)

```java
long P = 8800000000L;
```

### (e)

```java
char letter = 'U';
```

### (f)

```java
final String PRO = "Java";
```

## Question 5

### (a)

```java
double AMOUNT = 32.5;
AMOUNT += 10;
System.out.println("The amount is " + AMOUNT);
```

### (b)

```java
String chapter = "Summary";
System.out.println(chapter);
```

### (c)

```java
int num = 0;
num++;
int num1 = num;
```

### (d)

```java
double num = 3000;
System.out.printf("%4.2f\n", num);
```

### (e)

```java
String contact;
Scanner keyboard = new Scanner(System.in);
contact = keyboard.nextLine();
```

## Question 6

```text
Enter diameter: 11.8
The circumference of the circle is : 37.071
```

```java
import java.util.Scanner;

public class CircleCircumference {
    public static void main(String[ ] args) {
        Scanner keyboard = new Scanner(System.in);

        System.out.print("Enter diameter: ");
        double diameter = keyboard.nextDouble();

        double circumference = Math.PI * diameter;

        System.out.printf("The circumference of the circle is : %.3f%n", circumference);
    }
}
```

## Question 7

```text
Enter value in inch: 20.17
20.17 inches = 0.51 meters
```

```java
import java.util.Scanner;

public class InchToMeter {
    public static void main(String[ ] args) {
        Scanner keyboard = new Scanner(System.in);

        System.out.print("Enter value in inch: ");
        double inches = keyboard.nextDouble();

        double meters = inches * 2.54 / 100;

        System.out.printf("%.2f inches = %.2f meters%n", inches, meters);
    }
}
```
