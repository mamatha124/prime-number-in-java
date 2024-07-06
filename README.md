# prime-number-in-java
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int c=0;
        for (int i=2;i<n/2;i++){
            c=0;
            if (n%i==0){
                c++;
                System.out.println("Not a prime");
                break;
            }
        }
        if (c==0||n==2||n==1)
         System.out.println("prime number");
    }
}
