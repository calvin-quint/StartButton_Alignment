# Windows 11 Start Button Alignment

This PowerShell script checks the compatibility of the Windows operating system and performs a specific task related to the taskbar position if the system is running Windows 11 or a compatible version.

## Prerequisites

Before using the script, ensure you have the following:

- Windows PowerShell is installed on your system.
- Administrative rights are available for modifying registry settings.
- Understand the implications of modifying registry settings.


## Usage

1. Download the Windows11_CompatibilityCheck.ps1 script from this repository.
2. Open PowerShell and navigate to the directory where the script is located.
3. Run the script using the command: .\StartButton.ps1

## How to Use

1. Run PowerShell as an administrator.
2. Navigate to the directory where the script is located.
3. Run the script using the command: .\StartButton.ps1

## Instructions

1. The script checks if the Windows version is compatible with a minimum required version.
2. If the version is supported, the script proceeds to check and potentially modify the taskbar position.
3. The taskbar position is set to the left if not already set to that position.


## Important Notes

- Understand the purpose of the script and implications of modifying registry settings.
- Test the script in a controlled environment before using it widely.
- Review the script and adapt it to your environment's requirements.
- Keep your sensitive information secure and follow best practices.

## License

This project is licensed under the terms of the GNU General Public License v3.0. For more details, please see the [LICENSE](LICENSE) file.

## Disclaimer

This script is provided as-is and may require modifications to fit your specific use case. Use it responsibly and ensure compliance with Azure AD and Exchange Online policies. The creators of this script are not responsible for any misuse or unintended consequences of its usage.
