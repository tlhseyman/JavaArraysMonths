package sample;
import java.util.Scanner;

public class UdemyDiziAylar {

  public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String[] motnhs={"January","February","March","April","June","July","August","September","October","November","December"};
        System.out.println("Please enter a number from 1 to 12 : ");
        int number = scanner.nextInt();
        System.out.println("Month of that selected number is : " + motnhs[number-1]);
    }
}
