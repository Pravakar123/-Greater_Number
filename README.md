import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        int number1, number2;
        Scanner s = new Scanner(System.in);
        number1 = s.nextInt();    
        number2 = s.nextInt();    
        if(number1 > number2) 
        {
            System.out.println( number1);          
        } 
        
        else 
        {
            System.out.println(number2);
        }    
    }
}
