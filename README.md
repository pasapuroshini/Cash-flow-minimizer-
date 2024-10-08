# Welcome to the Cash Flow Minimizer System README !!
---
This system minimizes the number of transactions among multiple banks in the different corners of the world that use different modes of payment. There is one world bank (with all payment modes) to act as an intermediary between banks that have no common mode of payment.
<img width="696" alt="Screenshot 2024-09-15 at 8 19 07 PM" src="https://github.com/user-attachments/assets/65326aac-b4f9-4ac8-996b-b131f31027ca">


This is represented below as a directed graph with the directed edge representing debts. 
<img width="801" alt="Screenshot 2024-09-15 at 8 20 12 PM" src="https://github.com/user-attachments/assets/724a1bea-e808-4098-8b83-863c764011fc">
<img width="831" alt="Screenshot 2024-09-15 at 8 20 38 PM" src="https://github.com/user-attachments/assets/3ed06b67-84c5-4053-8f37-a3658431c50c">





If (magnitude of x) < y => X is completely settled and so removed from the list.

If (magnitude of x) > y => Y is completely settled and so removed from the list.

If (magnitude of x) = y => X and Y both are completely settled and so both are removed from the list.

The same process is repeated for the remaining banks.

For the current example, the transactions for minimum cash flow are as follows:


<img width="813" alt="Screenshot 2024-09-15 at 8 22 06 PM" src="https://github.com/user-attachments/assets/567954d7-4f84-4e5c-8ac2-ea8801184f15">

So this is the required answer.

How to Use?
This system is completely menu-driven. So when you will run the C++ Application, it will guide you and show you the final output.
Below is the execution of our current example: image

Thank you!! Happy learning :)



Reference Images:




<img width="807" alt="Screenshot 2024-08-14 at 9 00 25 PM" src="https://github.com/user-attachments/assets/cda26379-bd8d-415a-88ba-e84e1aae9059">

<img width="805" alt="Screenshot 2024-08-14 at 9 00 38 PM" src="https://github.com/user-attachments/assets/aae18bfe-47c3-4137-9dbc-e6793d0e295e">

<img width="831" alt="Screenshot 2024-08-14 at 9 00 51 PM" src="https://github.com/user-attachments/assets/93db9e61-bb24-495a-840e-20a0e879165c">



