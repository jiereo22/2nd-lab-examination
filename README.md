import java.util.Scanner;

public class MovieTicket {
    public static void main(String[] args) {
    
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Movie Title: ");        String movieTitle = scanner.nextLine();
        
        System.out.print("Ticket Price: ");      double ticketPrice = scanner.nextDouble();
        
        System.out.print("Number of Tickets: ");        int numberOfTickets = scanner.nextInt();
        
        double totalCost = ticketPrice * numberOfTickets;
        
        System.out.println("=== MOVIE TICKET RECEIPT ===");
        System.out.println("Movie Title: " + movieTitle);
        System.out.println("Ticket Price: " + ticketPrice);
        System.out.println("Number of Tickets: " + numberOfTickets);
        System.out.println("Total Cost: " + totalCost);
        scanner.close();
        }
        }
