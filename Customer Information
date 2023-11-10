
/**
 * Description: To design and develop a Java application for a Theme Park Ride Ticketing System.
 * GroupMate: FARAH NUR QISTINA BINTI MOHD ZAIDI, AHMAD ZUHAIRIE BIN MD ZAIDI, SITI ZULAIKHA BINTI MARKHALIM
 * StudentId: AM2211012780, AM2211012824, AM2211012908
 * Date: 8/11/2023
 */

// Import statements
import java.util.List;
import java.util.LinkedList;

public class CustomerInformation {
    
    // Define the attributes
    private int custId;
    private String custName;
    private String custAge;
    private String custNum;
    private int counterPaid;
    
    // A list of tickets associated with the customer.
    private LinkedList<TicketInformation> tickets;

    // Constructor to initialize customer information.
    public CustomerInformation(int custId, String custName, String custAge, String custNum,int counterPaid) {
        this.custId = custId;
        this.custName = custName;
        this.custAge = custAge;
        this.custNum = custNum;
        this.counterPaid = counterPaid;
        this.tickets = new LinkedList<>();
    }

    // Method to add a ticket to the customer's list.
    public void addTicket(TicketInformation ticket) {
        tickets.add(ticket);
    }

    // Methods to set and get customer attributes.
    public void setAttributes (int custId, String custName, String custAge, String custNum, int counterPaid) 
    {
        this.custId = custId;
        this.custName = custName;
        this.custAge = custAge;
        this.custNum = custNum;
        this.counterPaid = counterPaid;
        this.tickets = new LinkedList<>();
    }

    public void setcustId (int custId) 
    {
        this.custId = custId;
    }

    public void setcustName (String custName) 
    {
        this.custName = custName;
    }

    public void setcustAge (String custAge) 
    {
        this.custAge = custAge;
    }

    public void setcustNum (String custNum) 
    {
        this.custNum = custNum;
    }
    
    public void setcounterPaid (int counterPaid) 
    {
        this.counterPaid = counterPaid;
    }

    public int getcustId ()
    {
        return custId;
    }

    public String getcustName () 
    {
        return custName;
    }

    public String getcustAge () 
    {
        return custAge;
    }

    public String getcustNum () 
    {
        return custNum;
    }
    
    public int getcounterPaid () 
    {
        return counterPaid;
    }

    // Method to get the list of tickets associated with the customer.
    public List<TicketInformation> getTickets() {
        return tickets;
    }
}
