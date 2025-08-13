# SCRUM DEVELOPMENT - VENDING MACHINE

To run the application:

At the terminal, run the following command:

**gradle clean (optional)**

**gradle build run**

# Type of Roles

## Customer

There are 3 types of customers:<br>
<img width="400" alt="image" src="https://github.com/user-attachments/assets/63e41bad-ce0f-4960-aaa8-445279081551" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/bbdc7d13-ea57-4df9-8efe-22723b093d8a" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/344265cf-8e54-4696-bfa6-7178f242ac6e" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/4601a84a-802f-4e87-8a88-b59abdb4840d" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/c6339cbb-3775-4e4a-a77e-0676ee7702b4" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/8f1b31e2-9883-40f5-95ef-b40865dbde7c" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/75b4aa1c-1ccd-4bf7-af1b-fa63f94731ef" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/c9c3192c-5101-4679-837b-79003f570a7b" />

1. Customers who wishes to create an account can click on the link at the bottom of our application which says:  
*"click here, to create an account"*

2. Customers who do not wish to create an account in our application can choose to continue as Guest:  
They can do so by clicking on the link which says:  
*"<Click here, to continue as guest!>"*

3. Customers who already has an account and are able to log in straight after starting the application.

**Rule:**
- Once the customer has created an account, their username and password will be stored and saved into our database, they then become an existing user. 
- Only owner users are able to change/modify their role to become a Seller/Owner/Cashier. 

## Seller 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/2856c840-9a1f-4fab-8048-c5a2d71c9af8" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/cf61130a-af69-49d8-ad1d-f1d60d9bdc8b" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/d0cf48d9-45a3-40a7-a3fe-21b0fa3023e0" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/509307b5-7107-458e-ab75-c7e078596e88" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/a4339002-449b-4da2-a0bb-8735c7b8c8cd" />

## Cashier 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/1a5f4b4c-cf99-44fc-a3a2-46c28ef3fb64" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/c42140c7-f6ef-4979-aa86-6a53538c86e8" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/a5a1f269-39c2-470c-86b4-e2b4edb9a396" />

Cashiers are existing users who are mainly allowed to modify the quantity of each currencies (cash reserve) available in our Vending Machine.  
At any point in time, there is a cancel button on each page on the top right hand corner which will lead the user back to the log in page. 

1. Log in using an existing Cashier account 
2. Click on any of the 3 operations that the Cashier can operate on.

**3A.** If cashier has clicked on *Report Available Cash*:  
→ It will produce a CSV report on the Available Cash our Vending Machine has.
    
**3B.** If cashier has clicked on *Summary Transaction*:  
→ It will produce a CSV report on the summary of transactions. 
    
**3C.** If cashier has clicked on *Modify Cash*:  

1. The application will prompt the cashier to a new page that displays the quantity of each of the available currencies our Vending Machine has.  
2. For each of the currencies, there are up and down arrows/buttons which represent increase or decrease quantity respectively.  
3. After clicking on the arrows/buttons on the currencies (if cashier wants to modify), the cashier can click on the button "Modify" at the bottom right.  
4. The application will then lead the cashier to a page that displays "Operation Complete" that feedbacks to the cashier that the quantity of the currencies has been successfully modified to the corresponding amount. At this stage, the cashier can choose to go back to the page of Operations (point 2) or log out.  
5. If cashier wishes to log out, they can click on the link "Click Me to log out" and the application will prompt them back to the log in page.  
6. If cashier wishes to go back to the page of operations, they can click on the button on the bottom right "BACK TO OPERATION". The application will lead them back to the page at point 2.
        
## Owner 

<img width="200" alt="image" src="https://media.github.sydney.edu.au/user/9189/files/375d6ed5-af1f-41b6-a1fe-8926d6d996e6" />
<img width="200" alt="image" src="https://media.github.sydney.edu.au/user/9189/files/7216de04-2305-454a-8494-d0766e6f54b7" />
<img width="200" alt="image" src="https://media.github.sydney.edu.au/user/9189/files/a0c32d2c-040a-4774-8192-98ef3cb1097f" />
<img width="200" alt="image" src="https://media.github.sydney.edu.au/user/9189/files/8370f8af-300f-43fe-997d-31c80fcf9992" />
<img width="200" alt="image" src="https://media.github.sydney.edu.au/user/9189/files/c405dbfe-9379-4d82-b7bb-46ef5671cfe7" />
