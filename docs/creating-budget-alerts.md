
# How to Create Budget Alerts

1. create a new role
    - Open Roles.		
    - Click Create role button.		
    - Choose AWS account.		
    - Click next.		
    - Attach `AWSBudgetsActionsWithAWSResourceControlAccess` Policy to it.		
    - CLick next.		
    - Type a name for that role.		
    - Click create role.

2. Switch to that role.		
    - Search for the role in the roles console.		
    - Click on the role link.		
    - Copy the Link to switch roles in the console.		
    - Paste the link in the browser URL window and Enter to switch to that role.

3. Budget Setup:		
    - Search for Budgets in the AWS Console and open it.		
    - Click Create Budget		
    - Customize (Advance) > Cost budget - Recommended		
    - Click Next		
    - Type the Budget name.		
    - Select the Period to be Daily.		
    - Enter your budgeted Amount ($): type 0.5 (half a dollar).		
    - Click Next		
    - Click Add an alert threshold.		
    - Set the Threshold by typing 100 in the Threshold box.		
    - Type your email in the Email recepients box.		
    - Click Next, then Create budget to finish and create the budget.		
    - Sign out of the account and repeat the process for Course 4 account.