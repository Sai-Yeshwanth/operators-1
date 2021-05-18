
class Arithmetic{
	String name;
	public void add(int a, int b)
	{
		System.out.println(a+b);
	}
	public void sub(int a, int b)
	{
		System.out.println(a-b);
	}
	public void div(int a, int b)
	{
		System.out.println(a/b);
	}
	public void mul(int a, int b)
	{
		System.out.println(a*b);
	}
}
public class Jala {

	public static void main(String[] args) {
		
		Arithmetic var = new Arithmetic();
		
		var.add(5,6);
		var.sub(10,5);
		var.div(15,3);
		var.mul(5,3);
	}

}
