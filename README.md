import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int N = scanner.nextInt();
        String numberString = Integer.toString(N);
        String replacedString = numberString.replace('0', '5');
        int result = Integer.parseInt(replacedString);
        System.out.println(result);
    }
}
