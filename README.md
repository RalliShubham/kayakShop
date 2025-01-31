# Kayak Rental System
Renting a kayak should be simple, whether you're planning a quick paddle or a week-long excursion. This Kayak Rental System makes it easy to manage rentals, track availability, calculate costs, and generate invoices.

## How It Works
This system handles everything from rental requests to returns, ensuring a smooth experience for both customers and shop owners. 

It includes:
  - Rental Management – Customers select from hourly, daily, or weekly rental options. The system checks availability and approves or denies requests.
  - Automated Invoicing – Once kayaks are returned, a detailed bill is generated, applying discounts for group rentals (3-5 kayaks).
  - Emergency Shutdown – In case of unexpected closures, rentals are halted immediately.
    
## Key Features
  **🛶 Flexible Rental Options**
        Customers can rent kayaks hourly ($10), daily ($30), or weekly ($50), with automated calculations for total rental cost and duration.

  **📉 Smart Inventory Tracking**
        The system tracks available kayaks in real time.
        If a rental request exceeds availability, it notifies the customer and prevents overbooking.
        
  **💰 Built-in Discounts**
        Renting 3 to 5 kayaks? Enjoy an automatic 30% discount on your total bill.

  **📝 Detailed Invoices**
        Every transaction includes:
        Customer name
        Number of kayaks rented
        Rental duration and total cost
        Any applicable discounts

  **🚨 Emergency Stop Feature**
        Need to close the shop suddenly? The EMERGENCY_STOP function halts all rentals immediately and sets availability to zero.

## Scenarios in Action

  **1️⃣ Standard Rental & Return**
        Customer requests kayaks, system checks availability, and approves the request.
        After use, kayaks are returned, and an invoice is generated.
        
  **2️⃣ Overbooking Prevention**
        A customer tries to rent more kayaks than available—the system denies the request and displays the current stock.
        
  **3️⃣ Applying Discounts**
        A customer renting 4 kayaks for a daily rate automatically receives a 30% discount on their bill.
        
  **4️⃣ Emergency Closure**
        Unexpected shop closure? The EMERGENCY_STOP function halts all transactions instantly.
        
## Tech Behind the System
- Python – Core programming language
- Object-Oriented Programming (OOP) – Efficient, modular design
- Conditional Logic – Prevents overbooking and applies discounts
- User Input Handling – Interactive rental requests and returns
  
## How to Use
1️⃣ Run the script and enter customer details when prompted.
2️⃣ Choose rental options and check availability.
3️⃣ Return kayaks to generate an invoice.
4️⃣ Use EMERGENCY_STOP if needed.

## Future Enhancements
**Online Booking System –** Enable customers to reserve kayaks in advance.
**GPS Tracking –** Monitor kayak locations in real-time.
**Loyalty Discounts –** Reward frequent renters with special offers.


This Kayak Rental System ensures a seamless experience for renters and shop owners alike. Whether it’s a solo paddle or a group adventure, renting a kayak has never been easier! 🚣‍♂️
