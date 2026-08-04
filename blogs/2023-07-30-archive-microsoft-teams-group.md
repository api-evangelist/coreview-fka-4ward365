---
title: "Archive Microsoft Teams group"
url: "https://coreview.helpjuice.com/archive-microsoft-teams-group"
date: "2023-07-30"
author: "Elisabetta Landoni"
feed_url: "https://coreview.helpjuice.com/questions.atom"
---
If you need to archive/delete a Microsoft Teams group using a CoreView custom action, you can import the script below. Custom action script: { "id": "45fca056-5c23-4728-a67f-096b270eb684", "title": "Teams - Archive Teams group", "description": "A custom action to archive a Teams group and set the SharePoint site read-only for Team members", "lastModified": "2021-05-10T07:29:10.4510000Z", "target": "Teams", "tags": [], "vars": [ { "name": "Guid", "type": "string", "isRequired": false } ], "params": [ { "name": "DisplayName", "type": "string", "isDefault": true } ], "columns": { "DisplayName": "
