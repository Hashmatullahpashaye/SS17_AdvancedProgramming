#Exception Handling (throw &throws)



public class throw_throws {

	static void jan() throws ArithmeticException{
		int x=5;
		int y=0;
		int z=x/y;
		throw new ArithmeticException();
	}
	
	public static void main(String args[]){
	try{
		jan();
	}
	catch (ArithmeticException k){
		System.out.println("Can't divide "+k);
	}
	}
}
