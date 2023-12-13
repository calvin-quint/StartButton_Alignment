Windows 11 Taskbar Position Script
Overview
This script checks if the current Windows version is Windows 11 or a compatible version. If the system meets the requirements, it sets the taskbar position to the left side. The script is designed to run on Windows PowerShell.

Prerequisites
PowerShell should be installed on the system.
The script is designed for Windows 11 or a compatible version.
Usage
Open PowerShell with administrative privileges.
Copy and paste the script into the PowerShell window.
Execute the script.
Script Logic
Check Windows Version:

The script first defines the minimum required Windows version ($minimumVersion).
It then checks if the current Windows version is greater than or equal to the minimum version.
Taskbar Position:

If the Windows version is supported, the script continues to set the taskbar position.
It defines registry-related variables, including the registry path, property name, new value, and value type.
Retrieves the current registry value for the taskbar position.
If the current value is not equal to the desired value (0), it updates the registry to set the taskbar position to the left.
Important Note
Ensure that you run the script with administrative privileges to modify the registry.
Script Output
If the taskbar position is successfully set to the left, the script will indicate the change.
If the taskbar is already set to the left, the script will note that no changes are needed.
Disclaimer
Use this script at your own risk. Modifying the registry can impact system behavior. Make sure to understand the script's functionality before executing it.
