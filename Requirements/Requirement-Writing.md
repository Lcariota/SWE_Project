# Requirements Writing 


## Version 1 
- UI design  
  - Self Regestration
    -  Account Self Regestration  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Customer must be able to create an account with a unique username and a password  
 &nbsp; &nbsp; &nbsp; Sign-In screen  
    -  Create Customer Sign-in  
 &nbsp; &nbsp; &nbsp; priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Customer must be able to sign in with their unique username and password  
    -  Create Admin Sign-in  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort : ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admin must be able to sign in with their unique username and password
  - Main page  
    -  Sort Inventory  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Main page must display avalible inventory from highest to lowest priced  
    -  Create Inventory search bar  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Main page must contain a search bar  
  - Inventory display  
    -  Dsiplay Inventory name  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Every inventory item must have a short name  
    -  Display Inventory picture  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Inventory items must show at least 1 picture per item  
    -  Display Inventory price  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Inventory item price must be in US dollars, formatted with a $ sign, contain commas and decimal points  
    -  Display Inventory discription  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Every inventory item must contain a brief discription  
  - Shopping cart screen  
    -  Display Shopping cart  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Users must be able to see all items in shopping cart and subtotal  
    -  Provide "Checkout" button  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Button must transition user to payment screen  
  - Payment screen  
    -  Display Payment  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Payment screen must ask for shipping address, credit card number, phone number and shipping speed option  
    -  Display Shipping speed options  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Payment screen must show Shipping options of Overnight, 3-Day or Ground  
    -  Display Grand Total  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Display subtotal, tax, shipping option = grand total  
    -  Display Credit card payment format  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Credit card boxes must ask for credit card number, experiation month and year and CVV  
  - Recipt screen  
    -  Display Receipt  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Receipt must show last 4 digits of credit card and shipping address  
- Technical design  
  - Login Screen  
    -  Add Account Self Regestration
 &nbsp; &nbsp; &nbsp;    Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Users must be able to create an account with a unique username and a password with at least 6 characters  
    -  Add Account login  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; User must be able to login with their credentials if they have already created an account   
  - Admin Login  
    -  Add account as admin  
 &nbsp; &nbsp; &nbsp; Priority - must have   
 &nbsp; &nbsp; &nbsp; Effort: 2 days  
 &nbsp; &nbsp; &nbsp; Functional   
 &nbsp; &nbsp; &nbsp; Admins only can transform customer account to admin account   
  - Main Screen   
    -  Create Inventory search bar  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Main page must contain a search bar that searches items based on name and discription   
    -  Create "Add to cart button"  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day 
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Users can add multiple items to move into the cart  
  - Shopping cart  
    -  Calculate Subtotal  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day 
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Shopping cart must display the subtotal of all items currently in the cart  
    -  Remove items from cart  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; User must have ability to remove items from cart  
  - Payment  
    -  Calcuate tax from subtotal  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Calculate tax from subtotal of items at 6% tax (subtotal + (subtotal * .06))  
    -  Calculate shipping cost option to total   
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Add Shipping cost fee to total (Overnight: $29, 3-Day: $19, Ground: $0)  
    -  Calculate Grand total   
 &nbsp; &nbsp; &nbsp; Priority - must have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Caclulate Grand total (Subtotal + (Subtotal * .06) + shipping cost)  
    -  Store Customer Information  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp;    Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Store customer shipping address, phone number, credt card information and total  
  - Recipt   
    -  Show recipt after complete order  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Receipt shows automatically after customer completes order   
  - Sales Report  
    -  Admin Sales report  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Only Admins can run sales reports showing WHO purchased WHAT   


## Version 2
- Future UI design  
  - Admin UI page  
    -  Create Admin promotion page  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Page allows admin to promote other customer account to admin status  
  - Future Inventory  
    -  Add multiple pictures to inventory  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Muliple photos can be upload to a single inventory item  
    -  Admin UI  to add inventotry  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; UI page created so Admins can easily add inventory   
- Future Technical design  
  - Future Sales report  
    -  Admin can export sales report  
 &nbsp; &nbsp; &nbsp; Priority - need to have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admins can export sales report easily to CSV   
     -  Sales Report receipts   
 &nbsp; &nbsp; &nbsp; Priority - need to have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 3 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admins can pull up the corresponding receipt to a sales report item  
    -   Future Recipts  
 &nbsp; &nbsp; &nbsp; Receipts can be emailed to customer   
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; After completeting order, a receipt is automatically emailed to the customer if email is on file  

