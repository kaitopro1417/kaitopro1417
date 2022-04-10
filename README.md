
import java.util.Scanner;

public class bt {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
        System.out.println("Nhap vao so nguyen n: ");
		int n = sc.nextInt();
		int sum = 0;
		for (int i = 1; i <= n; i++) {
			if (i % 5 == 0) {
				sum += i;
			}
		}
		System.out.println(sum);
	}
}
