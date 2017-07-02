class Addition
{
	int a=10;
	int b=20;
	short s;
	byte b1;
	long l;
	float f;
	double d;
	void add()
	{
		int c=a+b;
		System.out.println("The value of c is :"+c);
	}
  public static void main(String args[])
	{
	  Addition addition=new Addition();
	  addition.add();
	}
}
