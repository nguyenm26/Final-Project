# Final-Project
import java.util.Scanner;

public class FinalProject {
  public static void main(String [] args) {
    Scanner input = new Scanner(System.in); 
    
    //numb o fplayers
    System.out.println("Enter number of players, one or two. Not three of four: ");
    int numOfPlayers = input.nextInt();
    
    if (numOfPlayers == 1) {
        System.out.println("Enter player 1's name: ");
        String player1 = input.nextLine();
        
    }
    else if (numOfPlayers == 2) {
        System.out.println("Enter player 1's name: ");
        String player1 = input.nextLine();
        input.nextLine();
        System.out.println("Enter player 2's name: ");
        String player2 = input.nextLine();
        
    }
    System.out.println("Get in looser, we're going shopping!");
    
    int Number = (int)(Math.random() * 10); 
  }
}
