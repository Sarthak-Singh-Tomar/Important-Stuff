```
class Main {
	public static void main(String args[]) {
		System.out.println(decimalToBinary(10));
	}
	
	public static int decimalToBinary(int n) {
		// if(n==1) {
		// 	System.out.print(1);
		// 	return;
		// }
		// decimalToBinary(n/2);
		// System.out.print(n%2);
		if(n==0) {
			return 0;
		}
		return n%2 + 10*decimalToBinary(n/2);
	}
}
```
