# Installing Active Directory Domain Services

The first step in building the lab environment was installing Active Directory Domain Services on Windows Server 2022.

## Step 1 – Open Server Manager

After logging into Windows Server 2022, Server Manager opens automatically. This tool is used to install server roles and manage the system.

## Step 2 – Add Roles and Features

1. Click Manage in the top-right corner
2. Select Add Roles and Features
3. Choose Role-based or feature-based installation
4. Select the local server from the server pool

## Step 3 – Select the Server Role

From the list of roles, select:

Active Directory Domain Services

The wizard will prompt to install additional features required by Active Directory. These should be accepted.

## Step 4 – Install the Role

Continue through the wizard and click Install.

Once the installation finishes, the server will not yet be a Domain Controller. It must be promoted.

## Step 5 – Promote the Server to Domain Controller

After installation completes, a notification flag appears in Server Manager.

Click the notification and select:

Promote this server to a domain controller

Select:

Add a new forest

Root domain name:

company.local

## Step 6 – Configure Directory Services Restore Mode

A password must be created for Directory Services Restore Mode (DSRM). This password is used for recovery scenarios.

## Step 7 – Complete Installation

Continue through the remaining configuration steps and click Install.

The server will restart automatically and become the Domain Controller for the domain.
