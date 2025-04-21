import java.util.Scanner;

public class cta4 {
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		double[] grades = new double[10];
		double sum = 0;
		double max = Double.MIN_VALUE;
		double min = Double.MAX_VALUE;
		
		System.out.println("Enter 10 grades one by one:");
	for (int i = 0; i < grades.length; i++) {
		System.out.print("Grade " + (i + 1) + ": ");
		
		while (!scanner.hasNextDouble()) {
            System.out.println("Please enter a valid grade: ");
            scanner.next();
		}
		
		double grade = scanner.nextDouble();
		grades[i] = grade;
		sum += grade;
		if (grade > max) max = grade;
		if (grade < min) min = grade;
	}
	
	double average = sum / grades.length;
	
	System.out.println("\nGrades:");
    System.out.printf("Average: %.2f\n", average);
    System.out.printf("Maximum: %.2f\n", max);
    System.out.printf("Minimum: %.2f\n", min);
    
    scanner.close();
	}
}
