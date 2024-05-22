# hello
import java.util.*;
class Sum{
int a,b,c;
public static void main(String ar[]){
Sum ob=new Sum();
Scanner sc=new Scanner(System.in);
System.out.println("enter any number");
ob.a=sc.nextInt();
ob.b=sc.nextInt();
ob.c=ob.a+ob.b;
System.out.println("sum of : " + ob.c);
}
}
