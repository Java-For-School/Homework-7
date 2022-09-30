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
Variable | num1 | num2 | num3 | d1 | d2 | d3 |  
--- | --- | --- | --- |--- |--- |--- |--- |
Value | 301 | 283 | 290 | 286 | 289 | 285 | 
