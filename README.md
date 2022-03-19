# Outlook2Notion

Python scripts to semi-automate the tracking of outlook communications (emails, attachments) into Notion. These tools make use of python and the NOTION API. The idea is to avoid the use of third party services like Zapier, Automate.io...etc. This can be usualy the case when you work for an institution with strict cybersecurity rules or you prefer to keep your files in a service that you trust more (e.g. Dropbox, Google Drive).
The goal is twofold: 1) to have an outlook "companion" to assist in the tracking of mails in notion, 2) to do so by keeping important information in institutional or private storage.

Example use case:
An important email arrives with a confidential attachment.
- The attachement is saved in a dedicated instituional OneDrive project folder in compliance with instituional cybersecurity rules 
- A private Notion database is updated with minimal information about the document (name, date, project name) and a link to the actual saved document.

