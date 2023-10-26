# Requirements Writing 


**Version 1**
- UI design  
  - Self Regestration T2E-1  
    -  Account Self Regestration T2S-1  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Customer must be able to create an account with a unique username and a password  
  - Sign-In screen T2E-2  
    -  Create Customer Sign-in T2S-2  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Customer must be able to sign in with their unique username and password  
    -  Create Admin Sign-in T2S-3  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort : ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admin must be able to sign in with their unique username and password
  - Main page T2E-3  
    -  Sort Inventory T2S-4  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Main page must display avalible inventory from highest to lowest priced  
    -  Create Inventory search bar T2S-5  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Main page must contain a search bar  
  - Inventory display T2E-4  
    -  Dsiplay Inventory name T2S-6  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Every inventory item must have a short name  
    -  Display Inventory picture T2S-7  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Inventory items must show at least 1 picture per item  
    -  Display Inventory price T2S-8  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Inventory item price must be in US dollars, formatted with a $ sign, contain commas and decimal points  
    -  Display Inventory discription T2S-9  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Every inventory item must contain a brief discription  
  - Shopping cart screen T2E-5  
    -  Display Shopping cart T2S-10  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Users must be able to see all items in shopping cart and subtotal  
    -  Provide "Checkout" button T2S-11  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Button must transition user to payment screen  
  - Payment screen T2E-6  
    -  Display Payment T2S-12  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Payment screen must ask for shipping address, credit card number, phone number and shipping speed option  
    -  Display Shipping speed options T2S-13  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Payment screen must show Shipping options of Overnight, 3-Day or Ground  
    -  Display Grand Total T2S-14  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Display subtotal, tax, shipping option = grand total  
    -  Display Credit card payment format T2S-15  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Credit card boxes must ask for credit card number, experiation month and year and CVV  
  - Recipt screen T2E-7  
    -  Display Receipt T2S-16  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Receipt must show last 4 digits of credit card and shipping address  
- Technical design  
  - Login Screen  T2E-8  
    -  Add Account Self Regestration T2S-17  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Users must be able to create an account with a unique username and a password with at least 6 characters  
    -  Add Account login T2S-18  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; User must be able to login with their credentials if they have already created an account   
  - Admin Login  T2E-9  
    -  Add account as admin T2S-19  
 &nbsp; &nbsp; &nbsp; Priority - must have   
 &nbsp; &nbsp; &nbsp; Effort: 2 days  
 &nbsp; &nbsp; &nbsp; Functional   
 &nbsp; &nbsp; &nbsp; Admins only can transform customer account to admin account   
  - Main Screen T2E-10  
    -  Create Inventory search bar T2S-20  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Main page must contain a search bar that searches items based on name and discription   
    -  Create "Add to cart button" T2S-21  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day 
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Users can add multiple items to move into the cart  
  - Shopping cart T2E-11  
    -  Calculate Subtotal T2S-22  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day 
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Shopping cart must display the subtotal of all items currently in the cart  
    -  Remove items from cart T2S-23  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; User must have ability to remove items from cart  
  - Payment T2E-12  
    -  Calcuate tax from subtotal T2S-24  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Calculate tax from subtotal of items at 6% tax (subtotal + (subtotal * .06))  
    -  Calculate shipping cost option to total T2S-25  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Add Shipping cost fee to total (Overnight: $29, 3-Day: $19, Ground: $0)  
    -  Calculate Grand total T2S-26  
 &nbsp; &nbsp; &nbsp; Priority - must have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/4 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Caclulate Grand total (Subtotal + (Subtotal * .06) + shipping cost)  
    -  Store Customer Information T2S-27  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Store customer shipping address, phone number, credt card information and total  
  - Recipt T2E-13  
    -  Show recipt after complete order T2S-28  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Non-Functional  
 &nbsp; &nbsp; &nbsp; Receipt shows automatically after customer completes order   
  - Sales Report T2E-14  
    -  Admin Sales report T2S-29  
 &nbsp; &nbsp; &nbsp; Priority - must have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Only Admins can run sales reports showing WHO purchased WHAT   


**Version 2**
- Future UI design  
  - Admin UI page T2E-15  
    -  Create Admin promotion page T2S-30  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Page allows admin to promote other customer account to admin status  
  - Future Inventory T2E-16  
    -  Add multiple pictures to inventory T2S-31  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 1/2 day  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Muliple photos can be upload to a single inventory item  
    -  Admin UI  to add inventotry T2S-32  
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; UI page created so Admins can easily add inventory   
- Future Technical design  
  - Future Sales report T2E-17  
    -  Admin can export sales report T2S-33  
 &nbsp; &nbsp; &nbsp; Priority - need to have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admins can export sales report easily to CSV   
     -  Sales Report receipts T2S-34  
 &nbsp; &nbsp; &nbsp; Priority - need to have   
 &nbsp; &nbsp; &nbsp; Effort: ~ 3 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; Admins can pull up the corresponding receipt to a sales report item  
    -   Future Recipts T2S-35  
 &nbsp; &nbsp; &nbsp; Receipts can be emailed to customer   
 &nbsp; &nbsp; &nbsp; Priority - want to have  
 &nbsp; &nbsp; &nbsp; Effort: ~ 2 days  
 &nbsp; &nbsp; &nbsp; Functional  
 &nbsp; &nbsp; &nbsp; After completeting order, a receipt is automatically emailed to the customer if email is on file  

