# Requirements Writing 


## Version 1 
 &nbsp; UI design  
 &nbsp; &nbsp; Self Regestration  
 &nbsp; &nbsp; &nbsp; Account Self Regestration  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Customer must be able to create an account with a unique username and a password  
 &nbsp; &nbsp; Sign-In screen  
      Create Customer Sign-in 
        Priority - must have
        Effort: ~ 1/2 day
        Functional
        Customer must be able to sign in with their unique username and password 
      Create Admin Sign-in 
        Priority - must have
        Effort : ~ 1/2 day 
        Functional 
        Admin must be able to sign in with their unique username and password
    Main page
      Sort Inventory 
        Priority - must have
        Effort: ~ 1/2 day 
        Non-Functional
        Main page must display avalible inventory from highest to lowest priced 
      create Inventory search bar
        Priority - must have 
        Effort: ~ 1 day
        Functional 
        Main page must contain a search bar
    Inventory display
      Dsiplay Inventory name
        Priority - must have 
        Effort: ~ 1/4 day
        Non-Functional
        Every inventory item must have a short name 
      Display Inventory picture
        Priority - must have 
        Effort: ~ 1/2 day
        Non-Functional 
        Inventory items must show at least 1 picture per item 
      Display Inventory price 
        Priority - must have 
        Effort: ~ 1/4 day
        Non-Functional
        Inventory item price must be in US dollars, formatted with a $ sign, contain commas and decimal points
      Display Inventory discription
        Priority - must have 
        Effort: ~ 1/4 day
        Non-Functional
        Every inventory item must contain a brief discription 
    Shopping cart screen
      Display Shopping cart 
        Priority - must have 
        Effort: ~ 1 day
        Non-Functional
        Users must be able to see all items in shopping cart and subtotal
      Provide "Checkout" button
        Priority - must have 
        Effort: ~ 1/4 day
        Functional 
        Button must transition user to payment screen 
    Payment screen
      Display Payment 
        Priority - must have 
        Effort: ~ 2 day
        Non-Functional
        Payment screen must ask for shipping address, credit card number, phone number and shipping speed option 
      Display Shipping speed options
        Priority - must have 
        Effort: ~ 1/4 day
        Non-Functional
        Payment screen must show Shipping options of Overnight, 3-Day or Ground
      Display Grand Total 
        Priority - must have 
        Effort: ~ 1/4 day
        Functional
        Display subtotal, tax, shipping option = grand total 
      Display Credit card payment format 
        Priority - must have 
        Effort: ~ 1/2 day
        Functional
        Credit card boxes must ask for credit card number, experiation month and year and CVV
    Recipt screen
      Display Receipt  
        Priority - must have 
        Effort: ~ 1 day
        Functional
        Receipt must show last 4 digits of credit card and shipping address 
*Tabspace* Technical design
    Login Screen 
      Add Account Self Regestration
        Priority - must have 
        Effort: 1 day
        Functional 
        Users must be able to create an account with a unique username and a password with at least 6 characters
      Add Account login 
        Priority - must have 
        Effort: 1 day
        Functional 
        User must be able to login with their credentials if they have already created an account  
    Admin Login 
      Add account as admin
        Priority - must have 
        Effort: 2 days
        Functional 
        Admins only can transform customer account to admin account 
    Main Screen 
       Create Inventory search bar
        Priority - must have 
        Effort: ~ 1 day
        Functional 
        Main page must contain a search bar that searches items based on name and discription 
      Create "Add to cart button" 
        Priority - must have 
        Effort: ~ 1 day
        Functional 
        Users can add multiple items to move into the cart 
    Shopping cart 
      Calculate Subtotal 
        Priority - must have 
        Effort: ~ 1/4 day
        Functional 
        Shopping cart must display the subtotal of all items currently in the cart
      Remove items from cart
        Priority - must have 
        Effort: ~ 1/2 day
        Functional 
        User must have ability to remove items from cart 
    Payment
      Calcuate tax from subtotal 
        Priority - must have 
        Effort: ~ 1/4 day
        Functional
        Calculate tax from subtotal of items at 6% tax (subtotal + (subtotal * .06))
      Calculate shipping cost option to total 
        Priority - must have 
        Effort: ~ 1/4 day
        Functional
        Add Shipping cost fee to total (Overnight: $29, 3-Day: $19, Ground: $0)
      Calculate Grand total 
        Priority - must have 
        Effort: ~ 1/4 day
        Functional
        Caclulate Grand total (Subtotal + (Subtotal * .06) + shipping cost)
      Store Customer Information 
        Priority - must have 
        Effort: ~ 1 day
        Non-Functional
        Store customer shipping address, phone number, credt card information and total 
    Recipt 
      Show recipt after complete order 
        Priority - must have 
        Effort: ~ 1/2 day
        Non-Functional
        Receipt shows automatically after customer completes order 
    Sales Report
      Admin Sales report 
        Priority - must have 
        Effort: ~ 2 days
        Functional
        Only Admins can run sales reports showing WHO purchased WHAT 


## Version 2
 Future UI design
    Admin UI page
      Create Admin promotion page 
        Priority - want to have 
        Effort: ~ 1 day
        Functional
        Page allows admin to promote other customer account to admin status 
    Future Inventory
      Add multiple pictures to inventory 
        Priority - want to have 
        Effort: ~ 1/2 day
        Functional
        Muliple photos can be upload to a single inventory item 
      Admin UI  to add inventotry
        Priority - want to have 
        Effort: ~ 2 days
        Functional
        UI page created so Admins can easily add inventory 
 Future Technical design
Future Sales report
 Admin can export sales report
 Priority - need to have 
 Effort: ~ 2 days
 Functional
 Admins can export sales report easily to CSV 
 Sales Report receipts 
 Priority - need to have 
 Effort: ~ 3 days
 Functional
 Admins can pull up the corresponding receipt to a sales report item
 Future Recipts
 Receipts can be emailed to customer 
 Priority - must have 
 Effort: ~ 2 days
 Functional
 After completeting order, a receipt is automatically emailed to the customer if email is on file

