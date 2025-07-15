# Creating-User-in-AWS

In this example I will be creating a Full-Access Admin user in AWS to follow AWS best practices. 
Using the root account as little as possible in AWS is best practice. 

Step 1 - Login as the root user : 
     
     You will need access to the root account in order to create an IAM user with full-access. 

Step 2 - Navigate to IAM (Identity and Access Management) : 

<img width="935" height="469" alt="image" src="https://github.com/user-attachments/assets/1640bc7c-507a-4493-8477-b70ea50112e9" />

Step 3 - Navigate to Users and the Add users :

<img width="1907" height="554" alt="image" src="https://github.com/user-attachments/assets/77578225-7571-4453-b78e-d3f1779f274a" />

         Set the username 

<img width="1112" height="339" alt="image" src="https://github.com/user-attachments/assets/bb93fab3-a5b2-4569-9992-ccc281844ef5" />

         Allow access to the console - optional

Step 4 - Set Permissions

         Attach policies directly - find and select "AdministratorAccess". This will grant the user with full access
         to all AWS services.

<img width="1810" height="700" alt="image" src="https://github.com/user-attachments/assets/01d9d64c-ef84-4f1b-b919-a9dd08dae74c" />

         Select "Next", and then "Create User"

Notes :
To sign in as an IAM user, you will need the account ID (or Alias, which I will not be creating), IAM username and Password.
It is best practice to enable Multi-factor Authentication (MFA), but optional.

You can also automate this process with a bash script! 


<img width="1414" height="890" alt="image" src="https://github.com/user-attachments/assets/7b6ba152-14db-405f-b759-89511560b127" />
  
