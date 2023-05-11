import java.util.Scanner;
class Switchss
{
	public static void main(String[] args)
    {
		Scanner inputScore = new Scanner(System.in);
		System.out.print("Type grade is: " );
		String grade = "";
		int score = inputScore.nextInt();
		switch(score/10)
		{
			case 0: System.out.println("Is F"); break;
			case 1: System.out.println("Is F"); break;
			case 2: System.out.println("Is F"); break;
            case 3: System.out.println("Is F"); break;
            case 4: System.out.println("Is F"); break;
            case 5: System.out.println("Is F"); break;
            case 6: System.out.println("Is D"); break;
            case 7: System.out.println("Is C"); break;
            case 8: System.out.println("Is B"); break;
			case 9: System.out.println("Is A"); break;
			case 10: System.out.println("Is A"); break;
		}
	}
}
