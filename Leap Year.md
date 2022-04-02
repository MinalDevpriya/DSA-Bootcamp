# DSA-Bootcamp
//Input a year and find whether it is a leap year or not.
import java.util.Scanner;
public class leap_year {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("Enter a year");
        int year= in.nextInt();
        if(year%100==0) {
            if (year % 400 == 0) {
                System.out.println("leap year");
            } else {
                System.out.println("not leap year");
            }
        }
        else{
            if (year % 4 == 0) {
                System.out.println("leap year");
            } else {
                System.out.println("not leap year");
            }
            }
        }
    }
