# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.
## EQUIPMENT REQUIRED:
Hardware: Personal Computer (PC)

## DESIGN STEPS:

## INSTALLATION PROCEDURE:
## INSTALLING VMWARE:
### Step 1. Download VirtualBox
• Go to: https://www.virtualbox.org/
• Click on the “Downloads” link in the left menu
• Under VirtualBox x.x.x platform packages, click Windows hosts
<img width="724" height="433" alt="image" src="https://github.com/user-attachments/assets/5a840e34-8012-4383-9f0a-a6b25a1a6b67" />



### Step 2:
• Locate the downloaded .exe file (usually in your Downloads folder)
<img width="722" height="136" alt="image" src="https://github.com/user-attachments/assets/d71a4fa3-b664-4c98-855f-80251c5e32d6" />
• Double-click it to run the installer




### Step 3:
Installer Wizard
<img width="726" height="435" alt="image" src="https://github.com/user-attachments/assets/4e506a34-c646-40e5-add0-31c302396f46" />

• Click Next
• Keep default settings unless you want to change install location or features
• Click Next
### Step 4. 
Network Interface Warning
• Click Yes to proceed (this may temporarily disconnect your internet)
<img width="744" height="406" alt="image" src="https://github.com/user-attachments/assets/5ecf6fd4-1306-4ef1-b57d-2103ddbbdaf6" />
### Step 5. Begin Installation
• Click Install
<img width="703" height="361" alt="image" src="https://github.com/user-attachments/assets/d9fdb02b-7879-4dcd-b99d-0e4c27d962de" />
• If asked for permission by User Account Control (UAC), click Yes
### Step 6. Finish Setup
• Click Finish
• VirtualBox will launch (if the checkbox is ticked)
<img width="682" height="349" alt="image" src="https://github.com/user-attachments/assets/2ea71c3a-eb16-484a-ac95-5d3f27df53c9" />
## INSTALLING KALI LINUX:
### Step 1: Open Oracle VirtualBox
• After installing VirtualBox, open it.
• The main screen of VirtualBox should appear.
### Step 2: Download Kali Linux VirtualBox Image
• Go to:
https://cdimage.kali.org/kali-2024.4/kali-linux-2024.4-virtualbox-amd64.7z
• Download the .7z file (Kali Linux VirtualBox image)
<img width="549" height="212" alt="image" src="https://github.com/user-attachments/assets/4317390d-d768-4876-befe-b75282e48a75" />
### Step 3: 
Extract the File
• Use 7-Zip or WinRAR to extract the .7z file:
o Right-click on the downloaded file
o Select "Extract Here" or "Extract to Folder"
• You’ll get a folder containing a .vbox file (VirtualBox Machine Definition
File)
### Step 4: 
Import Kali Linux into VirtualBox
• Open VirtualBox
• Click on File → Import Appliance
<img width="420" height="220" alt="image" src="https://github.com/user-attachments/assets/75f0f7f5-030d-45a9-afb8-2b13757c32a5" />
• Click Choose, then browse to the extracted .vbox file
• Select the .vbox file and click Next
• Keep the default settings as they are
• Click Import Wait for the import process to complete
Step 5: Start Kali Linux
• Once imported, you will see "Kali Linux" in the left panel
• Select it and click Start and the Kali Linux will boot up
<img width="600" height="277" alt="image" src="https://github.com/user-attachments/assets/b90345c2-05ce-4a9c-a600-b005ece98e4e" />
<img width="580" height="194" alt="image" src="https://github.com/user-attachments/assets/2c131a69-88e8-4f8e-864b-0d95c3489779" />
<img width="701" height="374" alt="image" src="https://github.com/user-attachments/assets/3e03aa79-4b9e-44b9-899e-58e18d4beb93" />
### Step 6: Use the Terminal in Kali Linux
• After login (default username: kali, password: kali)
• Open the Terminal (black monitor icon)
• Try the basic Linux commands:
<img width="1015" height="396" alt="image" src="https://github.com/user-attachments/assets/cc075bc4-7f05-49fc-b9e8-a5752ccf3162" />
## INSTALLING SLEUTH KIT:
• Download Sleuth Kit from www.sleuthkit.org/sleuthkit/download.php
<img width="673" height="363" alt="image" src="https://github.com/user-attachments/assets/d00a1e2e-061c-43ca-9f96-3aadb347fd55" />
● Move the downloaded folder to the program files.
● Go to the system environment variables.
<img width="1131" height="892" alt="image" src="https://github.com/user-attachments/assets/6e241c88-78c6-4a83-8dea-1419d81cd7f8" />
<img width="770" height="449" alt="image" src="https://github.com/user-attachments/assets/eb783d0b-c07b-4e83-8ca9-a199fc173d29" />
● Click environment variables.
<img width="788" height="361" alt="image" src="https://github.com/user-attachments/assets/68bdb131-e7f5-4e75-8fbf-bf3659c01c01" />
<img width="532" height="257" alt="image" src="https://github.com/user-attachments/assets/92bbbf9c-6a35-4b17-b44f-352e40c9b06c" />
● Click the path
● Now add the sleuth kit folder address.
● And the click ok. USING OF SLEUTH KIT:
<img width="524" height="181" alt="image" src="https://github.com/user-attachments/assets/c124ec79-5b8f-42d4-9242-387ab2c0d71d" />
● Open command prompt and type fls -V to check sleuth kit is installed or
not.
● Lists partition layout
<img width="751" height="376" alt="image" src="https://github.com/user-attachments/assets/e8b9f8f8-a13e-4d52-ae0e-3e040e31cfbc" />
● Lists files and directories
<img width="746" height="377" alt="image" src="https://github.com/user-attachments/assets/a1b9e3ec-af87-433c-83fd-808605b660cd" />
These are the some of the commands used in the Sleuth kit.
## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
