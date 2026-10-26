Q1.
(a)
public class Test{
            public static void main (String[]args){
if(3*8==27){
System.out.println(“3*8 =27”);
  }else{
 System.out.println(“3*8!=27”);
                                                                     }
                       }
}
(b)
import java.util.Scanner;

public class Test{
     public static void main(String[]args){
            Scanner sc=new Scanner(System.in);
            System.out.println(“Enter an integer please:”);
            int num=sc.nextInt();
            if(num%2==0){
               System.out.println(“Even number”);
           }else{
               System.out.println(“Odd number”);
           }
     }
}
(c)
import java.util.Scanner;

public class Test{
     public static void main(String[]args){
            Scanner sc=new Scanner(System.in);
            System.out.print(“Enter a character please:”);
            char ch=sc.next().charAt(0);
            if(ch>=‘A’&&ch<=‘Z’){
                System.out.println(“It is a capital letter”);
            }else{
                 System.out.println(“Not a capital letter”);
}
      }
}


(d)
public class Test{
     public static void main(String[]args){
          String s1=“Apple”;
          String s2=“banana”;
          if(s1.compareToIgnoreCase(s2)<0){
              System.out.println(s1+“,”+s2);
          }else{
              System.out.println(s2+“,”+s1);
          }
    }
}
(e)
import java.util.Scanner;

public class Test {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number 0-6：");
        int day = sc.nextInt();
switch (day) {
             case 0:
                System.out.println("Sunday");
                break;
             case 1:
                System.out.println("Monday");
                break;
             case 2:
                System.out.println("Tuesday");
                break;
             case 3:
                System.out.println("Wednesday");
                break;
             case 4:
                System.out.println("Thursday");
                break;
             case 5:
                System.out.println("Friday");
                break;
             case 6:
                System.out.println("Saturday");
                break;
        }
    }
}
Q2
(a)if (num1==num2)
(b)if(x>y&&y>z)
(c)if(s1.equals(s2))
   else
(d)if(x>0||y>0)





Q3
(a)
#####
$$$$$
(b)
#####
$$$$$
(c)
#####
(d)
No output

Q4
public class Test {
    public static void main(String[] args) {
        int a = 5, b = 9, c = 3;
        int max = a; 

        if (b > max) {
            max = b; // 
        }
        if (c > max) {
            max = c; // 
        }

        System.out.println("The biggest number is " + max);
    }
}

Q5
public class Test {
    public static void main(String[] args) {
        int year = 2026;

        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            System.out.println(year + " is a leap year");
        } else {
            System.out.println(year + " is not a leap year");
        }
    }
}

