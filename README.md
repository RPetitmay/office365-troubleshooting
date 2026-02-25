<p align="center">
<img src="https://i.imgur.com/mgcB5rf.png" alt="Traffic Examination"/>
</p>

<h1>Microsoft Office 365 Troubleshooting</h1>
This project demonstrates common Office 365 troubleshooting scenarios encountered in IT support roles. All scenarios were performed simulating an enterprise end-user workstation.<br />


<h2>Environments and Technologies Used</h2>
- Microsoft 365 Applications(OneDrive, Sharepoint)
- Browser-based troubelshooting

<h2>Operating Systems Used </h2>

- Windows 11 

<h2>List of Prerequisites</h2>

- Basic/General Understanding of Microsoft Azure
- Azure Subscription/Azure Account(Portal) created
- Resource Group created within your Azure portal
- Windows 11 Virtual Machine(Windows) created within your Azure portal with the resource group you've created previously

## Scenario 1: Outlook Login Issue

### Problem
User was unable to access email through the Outlook desktop application.

### Investigation
- Attempted Outlook sign-in on Windows Azure VM
- Verified credentials
- Tested access via Outlook Web Access to isolate account vs application issue

### Resolution
- Re-authenticated user account and verified successful mailbox access
- Confirmed Outlook functionality after remediation

### Lessons Learned
- Testing Outlook Web Access helps distinguish account issues from application-specific problems
- Browser-based access is a reliable troubleshooting step

## Scenario 2: OneDrive Sync Issue

### Problem
User reported OneDrive files were not syncing.

### Investigation
- Checked OneDrive client status
- Verified sign-in and internet connectivity
- Paused and resumed sync

### Resolution
- Re-authenticated OneDrive account
- Confirmed sync functionality restored

### Lessons Learned
- OneDrive sync issues are often client-side and resolved through reauthentication

## Scenario 3: SharePoint Access Denied

### Problem
User unable to access SharePoint document library.

### Investigation
- Verified user login context
- Tested access via browser
- Identified missing or incorrect permissions

### Resolution
- Confirmed correct access configuration
- Verified successful access after remediation

### Lessons Learned
- SharePoint access issues are commonly caused by permission misconfigurations

## Scenario 4: Password Reset Login Issue

### Problem
User unable to log in after password reset.

### Investigation
- Tested login via browser
- Cleared cached credentials
- Verified authentication behavior

### Resolution
- Removed cached credentials
- Confirmed successful login after reset

### Lessons Learned
- Cached credentials and sync delays can cause login issues after password resets
