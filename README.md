# AvgNumber
For my speech class, I demonstrated a 6 minuted speech on "How To Code" where I took couple of test grade and got the class average, and explained the importance in code in our everyday lives. 
public class DemoMain {
	public static void main(String[] args) {
		
		//1. CREATE THE PROJECT
		
		//test scores
		int[] array = {40, 70, 58, 87, 65, 33};
		
		//2. CREATE THE PLACEHOLDERS
		int sumOfAllScores = 0;
		int NumberOfStudents = array.length;
		int ClassAverage = 0;
		
		//3. FOR LOOP
		for (int i = 0; i < array.length; i++){
			
			sumOfAllScores += array[i]; //this will add all the numbers onto the sum.
			
		}
		
		//4. THE CALCUATION
		ClassAverage = sumOfAllScores/ NumberOfStudents; 
		
		//5. FINALLY, PRINTING OUT THE RESULT. 
		System.out.println( "The average of all the test scores in the class is " + ClassAverage);
	}
}
