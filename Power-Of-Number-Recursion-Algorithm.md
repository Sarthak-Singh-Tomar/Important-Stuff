```
class Main {
	public static void main(String args[]) {
		System.out.println(powerOfNumber(-2,5));
	}
	
	public static int powerOfNumber(int x, int n) {
		
		if(n<0) {
			return -1;
		}
		
		if(n==0) {
			return 1 ;
		}
		return x * powerOfNumber(x, n-1);
		
	}
	
}
		
```
