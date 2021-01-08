# Reverse-Method



public static void reverse()

{
	int revnum=0;
	
	Scanner input=new Scanner(System.in);
	System.out.println("Please enter a number");
	int num=input.nextInt();
	
	
	
	while(num!=0)
	{
	int digit=num%10;
	System.out.println(digit);

	
	revnum =revnum*10+digit;
	System.out.println(revnum);

	
	num/=10;
	System.out.println(num);

	
	System.out.println("=====================");

	}
	System.out.println(revnum);
	
	}
}
