## Lab
Create Organizational Units (OUs) in Active Directory

## Objective
Create Organizational Units (OUs) in the domain and organize the Sales department with child Organizational Units while protecting all OUs from accidental deletion.

## Environment
- Windows Server
- Active Directory Users and Computers (ADUC)
- Hyper-V
- Server
- Net.local Domain

## Steps Completed

### 1. Open the Domain Controller

- Open Hyper-V Manager.
- Select **SERVER**.
- Start and open **DC**.
- Maximize the window.

### 2. Open Active Directory Users and Computers
- Open **Server Manager**.
- Select **Tools**.
- Click **Active Directory Users and Computers**.

---

### 3. Create Organizational Units
Right-click **.local**
Select:
New → Organizational Unit

Create the following OUs:
- Accounting
- Admins
- Marketing
- Research-Dev
- Sales
- Servers
- Support
- Workstations

For every OU:

- Enter the OU name.
- Leave **Protect container from accidental deletion** checked.
- Click **OK**.

---

### 4. Create Child OUs under Sales

Expand:
.local
Right-click **Sales**
Select:
New → Organizational Unit
Create:
- SalesManagers
- TempSales

For both:
- Leave **Protect container from accidental deletion** enabled.
- Click **OK**.

## Skills Demonstrated

- Active Directory administration
- Organizational Unit creation
- Active Directory hierarchy
- OU management
- Protecting OUs from accidental deletion
- Windows Server administration


## Result
Successfully created all required Organizational Units within the **.local** domain, including nested Sales OUs, with accidental deletion protection enabled.
