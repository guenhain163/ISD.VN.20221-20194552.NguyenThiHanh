# Basic Flow / Success Flow
1. The customer requests to place an order on the view cart screen.
2. The AIMS software checks the availability of products in the cart.
3. The AIMS software displays the form of delivery information and delivery methods.
4. The customer chooses the delivery method.
5. The AIMS software checks for fast delivery and updates the results.
6. The customer enters and submits delivery information.
7. The AIMS software checks the validity of delivery information.
8. The AIMS software calculates shipping fees.
9. The AIMS software displays the invoice.
10. The customer confirms to place order.
14. The AIMS software calls UC “Pay order”.
15.The AIMS software saves invoice information and empties the cart.
16. The AIMS software displays success order.

# Alternative Flows
2a. If there is media of which quantity in the stock is less than the ordered quantity.
2a1. The AIMS software asks the customer to update the cart.
2a2. The customer updates the cart.
5a. The customer choose Place rush order.
5a1. The AIMS software calls UC “Place rush order”.
7a. If a mandatory field is left bank.
7a1. The AIMS software asks the customer to fill all the mandatory.
7b. If the phone number is invalid.
7b1. The AIMS software asks the customer to enter a valid phone number.
