# loop
to show switch statement
package switchchoice;
import java.util.*;
public class Choice {

	public static void main(String[] args) {
	int choice;
	System.out.println("pick ur choice");
	Scanner s=new Scanner(System.in);
	choice =s.nextInt();
	switch(choice)
	{
	case 1: System.out.println("hey");
	break;
	case 2: System.out.println("hi");
	break;
	case 3: System.out.println("hello");
	break;
	default: System.out.println("invalid choice");
	break;

	}

	}
