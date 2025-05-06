import java.util.Scanner;

public class Calculatepercentage {
    public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);

            int subject1, subject2, subject3, subject4, subject5;
            double totalmarks, percentage;

            System.out.println("Enter marks for 5 subjects: ");

            System.out.println("Enter marks for subject 1: ");
            subject1 = scanner.nextInt();

            System.out.println("Enter marks for subject 2: ");
            subject2 = scanner.nextInt();

            System.out.println("Enter marks for subject 3: ");
            subject3 = scanner.nextInt();

            System.out.println("Enter marks for subject 4: ");
            subject4 = scanner.nextInt();

            System.out.println("Enter marks for subject 5: ");
            subject5 = scanner.nextInt();

            totalmarks = subject1 + subject2 + subject3 + subject4 + subject5;

            percentage = (totalmarks / 500.0) * 100;

            System.out.println("\n----- Result -----");
            System.out.println("Total Marks: " + totalmarks);
            System.out.println("percentage: " + percentage);
            scanner.close();
        }

    }

