# AD Bulk Group Removal

## Overview
A PowerShell script to remove multiple users from multiple Active Directory groups in one go.  
This helps automate offboarding, cleanup, and access revocation tasks efficiently.

## Features
- Removes a list of users from multiple AD groups  
- Suppresses confirmation prompts for automation  
- Skips errors silently if users are not in a group  
- Provides a completion message when done  

## Usage
1. Open **PowerShell** as Administrator.  
2. Ensure the **Active Directory module** is installed.  
3. Update the script variables:
   - `$users` → List of usernames or sAMAccountNames  
   - `$groups` → List of AD groups  
4. Run the script:
   ```powershell
   .\Bulk-Group-Removal.ps1
