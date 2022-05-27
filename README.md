# harmonikNumber
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int number;
        double result = 1.0;
        Scanner input = new Scanner(System.in);
        System.out.println("Bir say giriniz : ");

        number = input.nextInt();
        for(int i=2; i<=number;i++){
            result = result + 1.0/i;
        }
        System.out.println(result);
    }
}
