# Tutorial 04

## Question 1

### 1a
```java
public class Q1a {
    public static void main(String[] args) {
        int n = 1;
        while ((n + 1) * (n + 1) * (n + 1) < 2000) {
            n++;
        }
        System.out.println("The largest integer n so that n^3 is less than 2000 is: " + n);
    }
}
```

### 1b
```java
public class Q1b {
    public static void main(String[] args) {
        for (int i = 1; i <= 12; i++) {
            System.out.println(i + " squared = " + (i * i));
        }
    }
}
```

### 1c
```java
public class Q1c {
    public static void main(String[] args) {
        int[][] matrix = new int[4][5];

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 5; j++) {
                matrix[i][j] = (int) (Math.random() * 101);
            }
        }

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 5; j++) {
                System.out.printf("%4d", matrix[i][j]);
            }
            System.out.println();
        }
    }
}
```

### 1d
```java
import java.util.Scanner;

public class Q1d {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int number = input.nextInt();

        int sum = 0;
        for (int i = 1; i <= number; i++) {
            sum += i;
        }

        System.out.println("The sum of numbers from 1 to " + number + " is: " + sum);
        input.close();
    }
}
```

### 1e
```java
public class Q1e {
    public static void main(String[] args) {
        double sum = 0;
        for (int i = 1; i <= 25; i++) {
            sum += (double) i / (26 - i);
        }
        System.out.printf("The sum of the series is: %.2f%n", sum);
    }
}
```

## Question 2

### 2a
```java
public class Q2a {
    public static void main(String[] args) {
        int x;
        int sum = 0;

        for (x = 10; x > 0; x--) {
            sum += x;
        }

        System.out.println("Sum = " + sum);
    }
}
```

### 2b
```java
public class Q2b {
    public static void main(String[] args) {
        int x = 0;
        int y = 0;

        do {
            x += 2;
            y += x;
            System.out.println(x + " and " + y);
        } while (x < 100);
    }
}
```

### 2c
```java
public class Q2c {
    public static void main(String[] args) {
        for (int x = 1, y = 20; x < y; x++, y -= 2) {
            System.out.println(x + " " + y);
        }
    }
}
```

### 2d
```java
public class Q2d {
    public static void main(String[] args) {
        int i = 1;

        while (i <= 10) {
            if (i == 10) {
                System.out.println("Program End");
            }
            i++;
        }
    }
}
```

## Question 3
```java
public class Q3 {
    public static void main(String[] args) {
        int f1 = 1;
        int f2 = 1;

        System.out.print(f1 + " " + f2);

        for (int i = 3; i <= 10; i++) {
            int f = f1 + f2;
            System.out.print(" " + f);
            f1 = f2;
            f2 = f;
        }

        System.out.println();
    }
}
```

## Question 4
```java
import java.util.Scanner;

public class Q4 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter a string: ");
        String s = input.nextLine();

        for (int i = s.length() - 1; i >= 0; i--) {
            System.out.print(s.charAt(i));
        }

        System.out.println();
        input.close();
    }
}
```
