## About
Application that verifies the registry editor based on the audit files. It offers parsing of
these files, selecting and creating new ones, checking they're values against the ones on the system
where the program is being launched, and enforcing these values in case they do not match.

## How to use
1. Activate venv
2. Run main.py
3. Click on download button to get the audits
4. Click import to select the needed audit file
5. Select configurations which you need
6. Save the desired selections(it will automatically save as .audit file)
7. Check if the configurations are applied to your OS

## Features
### Lab1 features 
• Import the manually downloaded policies from a predefined trusted location  
• Parse and understand the format of data within the imported policy  
• Save the same set of policies under a different name within a structured form (ex:database).    
### Lab2 features
• Choose which options they would like to run (by selecting or deselecting options)  
• Search by name for an option (via a search bar)  
• Select or deselect all options in one click  
• Create and save a policy that contains only the selected options under the same name or a different one.  
### Lab3 features
• Perform an audit of the workstation, using the options that were selected  
• Output the results of the audit on screen  
### Lab4 features
• Select the settings to be enforced (a subset of ”Failed”, or all of them)  
• Enforce the policy on at least 5 settings (edit the selected settings in your system)  
• Rollback to the system’s initial settings
### Lab5 features
• Select the settings to be enforced (a subset of ”Failed”, or all of them);
• Enforce the policy on at least 20 settings (edit the selected settings in your system);
• Rollback to the system’s initial settings
