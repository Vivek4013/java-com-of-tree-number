# java-com-of-tree-number

public class largest {
	public static void main(String[]args)
	{
	 int a,b,c largest,temp;	
	Scanner Sc=new Scanner(System.in);
		System.out.println("enter the first number");
		 int a1=Sc.nextInt();
		System.out.println("enter the second number");
		 int b1=Sc.nextInt();
		System.out.println("enter the third number");
		 int c=Sc.nextInt();
        temp=a1>b?a1:b;
        largest=c>temp?c:temp;
        System.out.println("the largest number is:"+largest);
        
		
	}

}
