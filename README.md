# count-no.-of-digits-in-a-number-in-java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int c=0;
        
        while(a>0){
            
            a=a/10;
            c++;
            
        }
        System.out.println(c);
       
      
    }
}
