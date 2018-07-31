# User-size-input-and-user-defined
The array size is dynamically allocated and the values are also entered by the user.
import java.util.Scanner;
class Test13
{
 public static void main(String args[])
{
 Scanner obj=new Scanner(System.in);
 System.out.print("Enter the no. of rows");
 int m=obj.nextInt();
 System.out.println("Enter the no. of columns");
 int n=obj.nextInt();
 int num[][]=new int[m][n];
System.out.println("enter the values");
for(int i=0;i<m;i++)
{
 for(int j=0;j<n;j++)
{
 num[i][j]=obj.nextInt();
}
}
System.out.println("You entered");
for(int i=0;i<m;i++)
{
for(int j=0;j<n;j++)
{
 System.out.print(num[i][j]+" ");
}
System.out.println();
}
}
}
