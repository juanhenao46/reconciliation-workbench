# Privacy Policy for Reconciliation Workbench

Last updated: September 18, 2026

## Overview
Reconciliation Workbench is an add-on for Google Sheets designed to reconcile and compare datasets directly within your spreadsheets. We take your privacy very seriously.

## Data Collection and Storage
- **No External Data Collection:** Reconciliation Workbench **does not** collect, store, or transmit your spreadsheet data, financial records, or personal information to any external server or third party.
- **In-Memory Execution:** All data comparison, normalization, and reconciliation logic executes entirely in-memory within your Google Workspace environment via Google Apps Script.
- **Local Presets:** Saved presets and configuration rules are stored strictly within your Google account using Google's native `PropertiesService` (`UserProperties`).

## Scopes and Permissions
Reconciliation Workbench uses the principle of least privilege:
- `https://www.googleapis.com/auth/spreadsheets.currentonly`: Allows the add-on to view and edit only the specific spreadsheet where you launch it. It cannot access any other file in your Google Drive.
- `https://www.googleapis.com/auth/userinfo.email` and `userinfo.profile`: Basic profile identification provided by Google Workspace.

## Limited Use Disclosure
Reconciliation Workbench's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Contact
If you have any questions about this Privacy Policy, please open an issue in this repository or contact the developer via GitHub.
