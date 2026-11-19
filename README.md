# IT-Support-Systems-Administration-Home-Lab

## Project Overview

This project is a practical introduction to IT support and systems administration. It involves building a virtual IT environment and using it to practise tasks that are commonly carried out by IT support teams.

Using VirtualBox and Windows Server 2022, the project covers setting up a server, creating a domain, managing user accounts and controlling access to shared resources.

It also includes ten realistic helpdesk scenarios based on common problems employees might experience at work, such as being unable to log in, connecting to a network or printing documents.

Each task is documented step by step, including the tools used, how the problem was investigated, what actions were taken and how the results were checked. Screenshots and relevant commands are included where appropriate to show the work carried out.

The aim is to develop practical skills, build confidence using IT tools and gain a better understanding of how everyday IT support issues are handled.

## Project Objectives

- Build and configure a virtual IT environment.
- Install and configure Windows Server and Active Directory.
- Create and manage user accounts, organisational units and security groups.
- Practise resetting passwords, unlocking accounts and managing user access.
- Learn how to use PowerShell to carry out everyday administrative tasks.
- Use Event Viewer to investigate system and security-related events.
- Troubleshoot common network, hardware and software problems.
- Work through realistic first-line and second-line IT support scenarios.
- Use Jira Service Management to record and manage support tickets.
- Document each task clearly, including the steps taken, results and lessons learnt.

## Tools & Technologies

| Tool / Technology | How it is used |
|---|---|
| Oracle VirtualBox | To create and run virtual computers. |
| Windows Server 2022 | To provide the server operating system for the lab. |
| Active Directory Domain Services | To manage user accounts, computers and access within the domain. |
| DNS | To help computers find servers and other network resources. |
| Active Directory Users and Computers | To create and manage users, groups and organisational units. |
| Windows PowerShell | To run commands and carry out administrative tasks. |
| Event Viewer | To review system logs and investigate errors. |
| Windows 11 | To practise common computer and user support issues. |
| Jira Service Management | To record, track and manage IT support tickets. |

## Virtual Environment

The project uses a virtual server created in VirtualBox. A virtual machine works like a separate computer, but runs inside the main computer rather than requiring another physical device.

The server has the following configuration:

| Configuration | Details |
|---|---|
| Server name | DC01 |
| Operating system | Windows Server 2022 Standard Evaluation |
| RAM | 4GB |
| Processors | 2 CPUs |
| Virtual disk | 50GB dynamically allocated |
| Domain name | lab.local |
| NetBIOS name | LAB |
| Server role | Domain Controller |
| Installed roles | Active Directory Domain Services and DNS |

## Project Tasks

### Task 01 – Virtual Machine & Windows Server Setup

Set up the virtual environment using Oracle VirtualBox. This includes downloading the Windows Server 2022 installation file, creating a virtual machine, installing the operating system and completing the initial server settings.

### Task 02 – Active Directory & Domain Configuration

Install Active Directory Domain Services and turn the server into a Domain Controller. Create a new domain and configure the basic settings needed to manage users and computers within the network.

### Task 03 – User, OU & Security Group Management

Create organisational units to keep user accounts organised, set up domain user accounts and create security groups. Add users to the appropriate groups and check that their accounts and permissions have been configured correctly.

### Task 04 – User Unable to Log Into Their Account

Investigate a scenario where an employee cannot log in because their account has been locked. Check the account in Active Directory, identify possible reasons for the lockout and practise unlocking the account. Also look at how to verify a user's identity before resetting their password.

### Task 05 – Outlook Not Sending or Receiving Emails

Investigate why an employee cannot send or receive emails through Microsoft Outlook. Check the connection, account status, offline settings and mailbox, and look at possible solutions such as restarting Outlook or creating a new Outlook profile.

### Task 06 – Employee Cannot Access Shared Network Drive

Investigate why an employee receives an access-denied message when trying to open a shared company folder. Check the network connection, the employee's group membership and the permissions controlling access to the folder.

### Task 07 – Laptop Connected to Wi-Fi but No Internet Access

Investigate a laptop that is connected to Wi-Fi but cannot access websites or online services. Use Windows commands to check the network settings, IP address, connection to the router and DNS settings to help identify the cause.

### Task 08 – User Unable to Connect to Company VPN

Investigate why an employee working remotely cannot connect to the company's VPN. Check their internet connection, VPN software, login details and access permissions, while considering possible network or security issues.

### Task 09 – Printer Not Responding

Troubleshoot a printer that is not printing documents. Check whether it is switched on and connected, review the print queue, investigate the printer drivers and check the Windows service responsible for managing print jobs.

### Task 10 – Computer Running Unusually Slowly

Investigate why a computer has become slow and unresponsive. Use Task Manager and other Windows tools to check memory, processor and disk usage, review available storage and look for programmes or background processes affecting performance.

### Task 11 – Employee Unable to Install Approved Software

Investigate why an employee cannot install an approved application on their computer. Check whether the software is already installed, review the user's account permissions and understand how software can be installed safely without giving unnecessary administrator access.

### Task 12 – Suspicious Email Reported by an Employee

Investigate an email that may be a phishing attempt. Look for warning signs, check the sender's details and identify any suspicious links. Consider what action should be taken if the employee has clicked the link or entered their login details, and how the incident should be reported.

### Task 13 – MFA Authentication Failure

Investigate why an employee cannot complete Multi-Factor Authentication (MFA) after replacing their mobile phone. Look at how authentication methods are registered, how failed sign-ins can be investigated and how an administrator can help the employee regain access securely.

## Documentation Approach

Each task has its own folder containing a README.md file. The documentation follows a consistent format so that the steps are easy to follow and the work can be reviewed later.

Each task covers:

- **Scenario:** A description of the problem or request being investigated.
- **Objective:** What needs to be achieved.
- **Tools Required:** The software, tools and commands needed.
- **Investigation:** The checks carried out to understand the problem.
- **Implementation:** The steps taken to resolve or address the issue.
- **Verification:** How the results are checked.
- **Evidence:** Screenshots, commands and other relevant findings.
- **Key Learnings:** What was learnt from completing the task.

## Project Outcomes

By completing these tasks, the project develops practical knowledge of Windows Server, Active Directory, user account management, PowerShell, networking, troubleshooting and IT service management.

It also provides an opportunity to practise approaching technical problems in a structured way, communicating findings clearly and understanding when an issue needs to be passed on to another team.

All exercises are carried out in a controlled lab environment or clearly identified simulations. The documentation reflects the work actually completed and the results obtained.
