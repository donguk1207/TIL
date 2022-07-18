# JAVA 기본문법 
## 예제 문제 풀기

```import java.util.Scanner; // Ctrl + Shift + o(영문자o)

public class HelloWorld {
```
	public static void main(String[] args) {
		/*
		 * String hello = "안녕하세요!"; System.out.println("hello"); System.out.println("안녕"
		 * + hello); System.out.printf("형식지정자를 사용 가능 %d\n", 10); String newstr =
		 * "새로운 문자열"; System.out.println("print,println,printf");
		 */

		// scanner 클래스를 사용하여 입력 받을 수 있음.
		/*
		 * Scanner sc = new Scanner(System.in);
		 * 
		 * System.out.print("당신의 이름은?:"); String name = sc.next();
		 * 
		 * System.out.print("숫자1 입력:"); int x = sc.nextInt(); //int값을 읽어들임 -> x로 대입
		 * System.out.print("숫자2 입력:"); int y = sc.nextInt(); //int값을 읽어들임 -> y로 대입
		 * 
		 * System.out.println("제 이름은 " +name + "입니다");
		 * System.out.printf("%d + %d = %d입니다.",x,y,x + y);
		 */

		/*
		 * System.out.println("     *"); System.out.println( "    ***");
		 * System.out.println("   *****"); System.out.println("  *******");
		 * System.out.println(" *********"); System.out.println("************");
		 */

		/*
		 * Scanner sc = new Scanner(System.in); System.out.print("정수를 입력하세요:"); int x =
		 * sc.nextInt(); System.out.printf("%d의 제곱은 %d입니다",x,x*x);
		 */

		/*
		 * Scanner sc = new Scanner(System.in); System.out.print("원기둥의 밑면 반지름은?:"); int
		 * x = sc.nextInt(); System.out.print("원기둥의 높이:"); int y = sc.nextInt();
		 * 
		 * double z = 3.14; System.out.printf("원기둥의 부피는 %f입니다.",z*(x*x)*y);
		 */

		/*
		 * Scanner sc = new Scanner(System.in); System.out.print("두 단위 정수를 입력하세요:"); int
		 * x = sc.nextInt(); System.out.printf("%d시간 %d분 %d초",x / (60*60), x %
		 * (60*60)/60, x % 60);
		 */

		/*
		 * Scanner sc = new Scanner(System.in); System.out.print("화씨온도:"); double x =
		 * sc.nextDouble(); System.out.printf("화씨 -> 섭씨:%f",5.0 / 9.0 * (x-32));
		 */