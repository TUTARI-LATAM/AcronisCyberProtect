# AcronisCyberProtect
Script's for Acronis Cyber Protect Installation


InstallerDLACRONIS.ps1 is a PowerShell script that helps with the installation of the Acronis Cyber Protect Cloud agent. This script validates administrator permissions and performs a clean installation if the software is not installed on the system. If the software is already installed, the script will skip the installation process. After validation, the script will proceed to download a ZIP package from a specific URL. Then, the script will read the MST and MSI files of the original offline installer, generate a log file, and notify the user of the steps taken.
