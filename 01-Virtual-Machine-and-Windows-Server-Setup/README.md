# Task 01 – Virtual Machine and Windows Server Setup

## Scenario
A virtual IT environment is required to practise common IT support and systems administration tasks without needing a separate physical server.

## Objective
Install and configure VirtualBox and create a virtual machine running Windows Server 2022.

## Tools Required
- Oracle VirtualBox
- Windows Server 2022 Evaluation ISO
- Host computer running Windows 11

## Investigation
- Check the host computer's hardware specifications and available storage.
- Confirm that hardware virtualisation is enabled.
- Review the system requirements before creating the virtual machine.

## Implementation
- Install Oracle VirtualBox.
- Download the Windows Server 2022 Evaluation ISO from Microsoft.
- Create a virtual machine named `DC01`.
- Allocate 4GB RAM, 2 CPUs and a 50GB dynamically allocated virtual hard disk.
- Install Windows Server 2022 Standard Evaluation (Desktop Experience).
- Rename the server to `DC01`.

## Verification
- Confirm that Windows Server starts successfully.
- Check the server name using the `hostname` command.
- Confirm that the virtual machine's allocated resources are correct.

## Evidence
- VirtualBox configuration and virtual machine settings.
- Windows Server desktop showing the successful installation.
- Command output confirming the server hostname.
- Relevant configuration details recorded during setup.

## Key Learnings
- Understanding virtualisation and how virtual machines work.
- Installing an operating system in a virtual environment.
- Allocating hardware resources to a virtual machine.
- Understanding the basic setup of a Windows Server environment.
