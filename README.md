# JAVA-EVEN
import java.util.Scanner;
class Even
{
    public static void main(String args[])
    {
	
        Scanner sc = new Scanner(System.in);
       
       System.out.print("Enter a number: ");
	
       long n=sc.nextLong();

       Evennumbers(n); 
          
    }

static void Evennumbers(long n)
{
	System.out.println("Even numbers are: ");
	
	for(long i=0;i<=n;i+=2)
	{
	System.out.print(i+"  ");
		
	}

}
}
