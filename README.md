# Fibanocci
import java.util.Scanner;
public class factorial {
	 
	private static Scanner fact;

	public static void main(String []arg){
		fact = new Scanner(System.in);
		int i,n;
		int a=0;
		int ans;
		System.out.println("enter the numberto get fibanocci");
		n = fact.nextInt();
		int count=0;
		for(i=1;i<=n;i++)
				{
					a=a+i;
					count++;
				}
		ans=a-count+1;
		System.out.println("The Fibanocci of "+n+" is "+ans);
				
	}

}
