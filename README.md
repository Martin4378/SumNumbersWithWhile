# SumNumbersWithWhile
import java.util.Scanner;

public class SumNumbers {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        String input = scanner.nextLine();
        int sum = 0;

        while (!(input.equalsIgnoreCase("stop"))){
            int CurrentNumber = Integer.parseInt(input);
            sum += CurrentNumber;
            input = scanner.nextLine();
        }
        System.out.println(sum);
    }
}
