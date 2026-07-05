## Create users & groups

### Objectives:
Understand what users & groups are in the Azure Active Directory and why they are
important.
Explain the basic concepts associated with creating users & groups in the Azure
Active Directory.
Define how to create users & groups in the Azure Active Directory.

# What is An AD?
An AD (active directory)/(Microsoft Entra ID) is a database that an organization creates to manage user's rights and authenticate them (making sure they are who they say they are).

### Why does an organization need users and groups in Azure Entra ID?
The reason these companies need users and groups is to allow certain people to have certain levels of priviliage(what they can see / Change).
You wouldnt want a random guy from finance to have Admin roles.

### Step 1: Navigate to Microsoft Entra ID
First, log in to the Azure Portal. Open the main portal sidebar menu, locate, and select **Microsoft Entra ID** from your favorites list.

![Navigate to Microsoft Entra ID](<img width="1134" height="740" alt="Screenshot 2026-07-05 151125" src="https://github.com/user-attachments/assets/46cba743-0a8f-45de-b5f9-5170f48aecd9" />)

---

### Step 2: Accessing Users or Groups Management
Once inside the Microsoft Entra ID overview console, locate the left-hand navigation sidebar under the **Manage** category:
* Click on **Users** to view, edit, or create individual accounts.
* Click on **Groups** to organize users into structural units for easier access management.

![Select Users or Groups](images/step2_users_groups.png)

---

### Step 3: Creating a New User Account
If you navigated to **Users** and clicked on **New user** -> **Create new user**, follow these input parameters:
1. **User principal name:** Enter the unique login identifier prefix before the organizational domain dropdown.
2. **Display name:** Provide the full recognizable identity name for the user profile.
3. **Password:** Keep the "Auto-generate password" checked or assign a temporary credential.
4. Finalize the initialization by clicking **Review + create** at the bottom-left corner.

![Create New User Form](images/step3_create_user.png)

---

### Step 4: Provisioning a New Group
If you navigated to **Groups** and selected **New group**, configure the following options:
1. **Group type:** Leave as **Security** to control access permissions for shared resources.
2. **Group name:** Enter an explicit name matching its administrative function.
3. **Members:** Click on the selection area to bind your newly created users into this group container.
4. Click **Create** to compile the group permissions.

![Create New Group Form](images/step4_create_group.png)
