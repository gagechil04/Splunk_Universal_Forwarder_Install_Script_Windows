# Splunk-Universal-Forwarder-Install-Script-Windows


-Place this script in the same directory as the Splunk Universal Forwarder MSI installer.

-Run as Administrator.

#This script will install the Splunk Universal Forwarder Application, set the username as "SplunkAdmin", generate a random password, and configures the UF as deployment client. 

## You will need to make a couple modifications within the script such as:
<br />• You will need to set the IP address of the Deployment Server within the script (or remove that flag all together if not applicable)
<br />• Ensure the filename of the MSI installer matches the file name referenced at the beginning of the script.

