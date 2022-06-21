```
class Main {
	public static void main(String args[]) {
		System.out.println(gcd(8,4));
	}
	
	public static int gcd(int a, int b) {
		
		if(a<0 || b<0) {
			return -1;
		}
		if(b==0) {
			return a;
		}
		return gcd(b, a%b);
	}
}
```
