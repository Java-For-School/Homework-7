# Homework-7

### Assignment 1:
```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int first, second;
        
        first = scanner.nextInt();
        second = scanner.nextInt();
        
        System.out.println(first % 10 + first / 10 % 10 == second % 10 + second / 10 % 10 ? "Yes" : "No");
    }
}
```
### Assignment 2:
```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int first, second;
        
        first = scanner.nextInt();
        second = scanner.nextInt();
        
        System.out.println(first % 10 == second % 10 || second / 10 % 10 == first / 10 % 10 ? "Yes" : "No");
    }
}
```
### Assignment 3:
![](https://i.imgur.com/AKQisxG.png)
| Variable | num1 | num2 | num3 | d1 | d2 | d3 |  
| --- | --- | --- | --- |--- |--- |--- |
Value | 45 | 5 | 135 | 5 | 5 | 5 | 
OUTPUT | -- | -- | YES | -- | -- | -- | 

The program receives an input of there numbers, determines whether their last digits are equal and outputs YES or NO according to the validity of the equality.
### Assignment 4:

![](https://i.imgur.com/wFVa8jp.png)
###### A:
| Variable | num1 | num2 | num3 |  
| --- | --- | --- | --- |
Value | 8 | 12 | 42 | 
OUTPUT | ALL-E | ALL-E | ALL-E |

###### B:
| Variable | num1 | num2 | num3 |  
| --- | --- | --- | --- |
Value | 5 | 63 | 81q | 
OUTPUT | ALL-O | ALL-O | ALL-O |

The program determines whether there numbers received as user input have their last digit divisible by two, and outputs ALL-E, ALL-O and Neither according to the results.
