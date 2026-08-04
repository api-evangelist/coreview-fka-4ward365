---
title: "How to automate Microsoft Entra Connect Directory Sync from CoreView"
url: "https://coreview.helpjuice.com/how-to-automate-microsoft-entra-connect-directory-sync-from-coreview"
date: "2025-06-11"
author: "Elisabetta Landoni"
feed_url: "https://coreview.helpjuice.com/questions.atom"
---
This procedure enables remote initiation of Microsoft Entra Connect sync cycles directly from CoreView, enhancing your hybrid environment automation and management. Note: Microsoft has renamed Azure Active Directory (Azure AD) to Microsoft Entra ID as of 2024. Step 1: Create a Scheduled Task on the Microsoft Entra Connect Server Create a scheduled task named RunScript that executes a PowerShell script to initiate an Microsoft Entra Connect synchronization.
