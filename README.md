# javaprime
Prime num
import java.util.Scanner;
class Prime
 {
   public static void main(String args[])
   {
     int num;
     int temp=0;
     System.out.println("enter any number");
     Scanner a= new Scanner(System.in);
     num=a.nextInt();
     for(int i=2;i<=num/2;i++)
     {
       if(num%i==0)
       {
         temp++;
       }
     }
     if(temp==0)
     System.out.println(num+" is prime");
     else
     System.out.println(num+" is not prime");
   }
 }
