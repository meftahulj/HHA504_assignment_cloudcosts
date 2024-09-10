# HHA504_assignment_cloudcosts
Monitor the costs associated with running VMs on GCP and Microsoft Azure

### 1. Cost Management Dashboard Location
#### Microsoft Azure

![Azure_dash](https://github.com/user-attachments/assets/68d95c67-34cf-487a-af50-214259cfcb72)


#### GCP

![GCP_dash](https://github.com/user-attachments/assets/de000cbc-7ba9-41c2-a5fa-08e202aefacc)

### 2. Set Up a Hypothetical Budget
#### Microsoft Azure

1. Creating the budget
![Azure_set_budget](https://github.com/user-attachments/assets/e442e799-fc1a-4897-8925-4297948131be)
2. Setting alert
![Azure_set_alert](https://github.com/user-attachments/assets/25fa1fe5-de9f-4a87-85e9-6b4ad3d18da3)

#### GCP

1. Creating the budget
![GCP_set_budget](https://github.com/user-attachments/assets/38c4f654-b255-47dc-8ab9-b16259ffa292)
2. Selecting the amount
![GCP_set_amount](https://github.com/user-attachments/assets/1c57c088-36d0-4d4c-a3b1-c4610e69a5b6)
3. Setting the actions
![GCP_set_actions](https://github.com/user-attachments/assets/9ecfa927-5966-442e-af30-29f2f3bb34c5)


### 3. Reflection
#### Microsoft Azure

Feature | Value
-|-
 Budget Scoping | Assigns a budget to a chosen scope such as a subscription or resource group. Can easily apply extra filters like resource groups or tags for more detailed monitoring which helps to manage expenses more precisely
Language prefrence|Lets users choose their preferred language for receiving budget alert emails to create seamless communication between all stakeholders

#### GCP
Feature | Value
-|-
Read-only for Project Users | Restricts project users from making unauthorized changes to budgets by marking them as read-only.
Scope Budget to Specific Resources | Enables the budget to focus on a specific set of resources such as folders, organizations, projects, or services, for more targeted cost management.
Credits | Applies selected credits to reduce the total tracked cost and reflects the net expenses after discounts are applied.
Set Alert Threshold Rules | Triggers email alerts when actual or forecasted spending exceeds a  percentage of the budget. Requires a minimum of three thresholds.
Manage Notifications | Provides options to receive notifications via email alerts to billing admins, users, or project owners, and supports linking monitoring channels and Pub/Sub topics for automated updates.
