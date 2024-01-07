**Setup Linux Subsystem (Ubunutu WSL-2)  on Windows**__

**_Step1_:**  **Check if Virtualization is enabled.**
   Go to Windows Task Manager, in the CPU tab check if “virtualization” is “enabled” or “disabled”. If “enabled”, proceed to next Step #2. 

If “disabled”, restart your machine, go to the BIOS, and enable virtualization.


Enable HyperV for windows

Open Windows “PowerShell” in Administrator Mode

Run the command - 
“Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform”

Please make sure this command is successfully run and your machine is restarted

Restart the windows after the above command is completed.

_**Step 2:**_ **Install Ubuntu from the below link, it will open Microsoft Store**
https://www.microsoft.com/store/apps/9PN20MSR04DW

Click on the “Get” button

Once the download is complete, Click on the “Open” button or go to the Windows start button, search “Ubuntu” and open the app.


The first time you launch a newly installed Linux distribution, a console window will open and you'll be asked to wait a minute or two for files to de-compress and be stored on your PC. All future launches should take less than a second.
Installing, this may take a few minutes…
You will then need to create a user account and password for your new Linux distribution. (PLEASE DO NOT FORGET THIS CREDENTIALS)

