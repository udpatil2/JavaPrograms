package Com.study;

import java.util.Scanner;

public class SubjectPercentageCalculator {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	
		        Scanner scanner = new Scanner(System.in);

		        int totalSubjects = 6;
		        int[] marks = new int[totalSubjects];
		        int totalMarks = 0;

		        // Taking input
		        for (int i = 0; i < totalSubjects; i++) {
		            System.out.print("Enter marks for Subject " + (i + 1) + ": ");
		            marks[i] = scanner.nextInt();
		            totalMarks += marks[i];
		        }

		        // Assuming each subject is out of 100
		        int maxTotal = totalSubjects * 100;
		        double percentage = (double) totalMarks / maxTotal * 100;

		        // Displaying result
		        System.out.println("Total Marks: " + totalMarks + "/" + maxTotal);
		        System.out.printf("Percentage: %.2f%%\n", percentage);

		        scanner.close();
		    

	}

}
