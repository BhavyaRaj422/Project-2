# Project-2
Created by:Bhavya Raj
import java.util.Scanner;
    public class Project{
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("Enter the minutes: ");
        double min = scan.nextDouble();
        long years = (long)(min/(60*24*365));
        long days = (long)(min/60/24)%365;
        System.out.println(min + " is approx "+years+"years &"+days+"days");

    }
}
