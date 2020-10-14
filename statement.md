# Practice with Loops

This Java template lets you get started quickly with a simple one-page playground.

```java runnable

public class Main {

    public static void main(String[] args) {

        //Create the trace table for this code.  Run the code to verify your answer.

        int sum = 0;
    
        for (int x = 1; x <= 15; x += 2) {
            sum += x;
            System.out.println("x: " + x);
            System.out.println("sum: " + sum);
        }
    
        System.out.println("final sum is: " + sum);
    }
}
```