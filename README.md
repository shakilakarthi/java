public class II {

	
	public static void main(String[] args) {
		
		{
			int n=525,n1,rev=0,rem;
		
			n1=n;
			while(n>0)
			{
				rem=n%10;
				rev=rev*10+rem;
				n=n/10;
			}
			if(n1==rev)
			{
				System.out.println(+n1+ " is Palindrome");
			}
			else
			{
				System.out.println(+n1+ " is not Palindrome");
			}
	}

	}
}
