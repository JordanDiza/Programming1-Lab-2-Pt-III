test test hello
Ticket price = 100 cents
Part III
#47
Nothing pretty much happens when I put 0
When I put a negative number the balance stays at 0 (they ask for a positive number greater than 0)
When I put a postive number for example 50 the balance goes to 50
When I put it a 0 the balance stays at 50
#48
I think that the balance will remain at 0
My prediction was wrong because the number has to be greater than 0
In the terminal they are asking me to use a positive amount rather than : 0
#49 
public void insertMoney(int amount)
    {
        if(amount <= 0) {
            System.out.println("Use a positive amount rather than: " + amount);
        }
        else {
            balance = balance + amount;
        }
    }
    When I put 50 the balance is at 50
    When I put 0 they ask for a positive amount same thing for negative numbers
#50 The feature was to make it visible or invisible I think.
    Yes, because you get to decide whether you make it visible or not
#51 so the difference is now you need to enter the exact amount of money needed for the tickets when you try printing it it say " that you need x amount of cents left" it doesn't print like on the naive ticket machine    
The compiles button still works
#52  I think if i remove "else" the ticket will just print even if you underpaid or overpaid
I removed "else" but the ticket still says that I am missing x amount of cents
Stuck dont know what to do
#53 it cannot become negative since it can't reach the amount needed to get a ticket
its like a real vending machine when you underpay they just give ur coins back
#54 * (for multiplication)
/ (division)
#55 int saving = price * discount;
#56 mean = total / count ;
#57    public void affordable(int budget){
// TODO: Write an if-statement that checks budget against price and prints
// a message saying weather a ticket is affordable
if (price > budget) {
    System.out.println("Too expensive");
} else {
    System.out.println("Good");
}
}
#58 if (price > budget) {
    System.out.println("Too expensive. Your budget is"+ budget + "cents");
} else {
    System.out.println("Good");
}
I feel like the easier method is the one used it 57 because it is way more simple than the 58 version
#59 well if I run refundBalance id expect it to give me my money back. When the balance is at 0 there is no money to refund this theres no balance to give back
#60