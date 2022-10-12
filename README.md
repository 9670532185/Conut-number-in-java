# Conut-number-in-java
import java.util.* ;
import java.io.*; 

public class Solution {
    static int countDigit(long x) {
        // Write your code here.
        int count=0;
        while(x>0)
        {
            x=x/10;
            count++;
        }
      //  System.out.println(count);
        return count;
    }
    public static void main(String[] args)
    {
        long n;
        Scanner obj=new Scanner(System.in);
        n=obj.nextLong();
        countDigit(n);
    }
}
