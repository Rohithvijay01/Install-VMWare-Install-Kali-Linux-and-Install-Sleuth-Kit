## Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### AIM:
To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

### DESIGN STEPS:
### Step 1:
Install VMware Workstation Player on your system and download the Kali Linux ISO from its official website.

### Step 2:
Create a new virtual machine in VMware using the Kali Linux ISO, configure the hardware settings, and complete the installation of Kali Linux.

### Step 3:
Open the terminal in Kali Linux and run the command sudo apt install sleuthkit to install Sleuth Kit.

### PROGRAM:
### Step 1: Install VirtualBox
 1. Download the Windows hosts .exe file from the official VirtualBox website.
 2. Run the installer and follow the on-screen instructions.
 3. Once installed, launch VirtualBox to verify the installation.

<img width="1014" alt="Screenshot 2025-04-21 at 1 42 29 AM" src="https://github.com/user-attachments/assets/66c137ec-ca91-4057-b7d8-1d6211904978" />



### Step 2: Install Kali Linux on VirtualBox
 1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).
 2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM.
 3. Go to Settings > Storage, click Empty under Controller: IDE.
 4. Select Graphical Install, follow the prompts to set language, location, username, and password.
 5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.
<img width="1010" alt="Screenshot 2025-04-21 at 1 42 58 AM" src="https://github.com/user-attachments/assets/5d5d6f9d-ae09-4045-befa-1ba23408a289" />



### Step 3: Install Sleuth Kit (CLI-based Forensic Tools)
 1. Download the Windows ZIP package from the official website.
 2. Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit).
 3. Add the bin folder to Windows PATH:
    * Open Control Panel → System → Advanced System Settings.
    * Click Environment Variables → Edit Path.
    * Add the Sleuth Kit bin folder path and save changes.
 4. Verify installation by running:
  ```
 fls -V

  ```

<img width="1016" alt="Screenshot 2025-04-21 at 1 44 19 AM" src="https://github.com/user-attachments/assets/80ce2733-ae13-41a7-92fb-2ae0c96be988" />


### OUTPUT:
### Virtual Box:

<img width="1013" alt="Screenshot 2025-04-21 at 1 46 06 AM" src="https://github.com/user-attachments/assets/74736722-f0db-47c7-aef6-f4796a13a60d" />


### Virtual Machine (Kali Linux):

<img width="1014" alt="Screenshot 2025-04-21 at 1 45 37 AM" src="https://github.com/user-attachments/assets/5d624456-caff-476e-a67d-aae680030916" />

### Sleuth Kit:
<img width="602" alt="Screenshot 2025-04-21 at 1 46 23 AM" src="https://github.com/user-attachments/assets/7af84480-0f11-47c0-a9a9-5178309ce9e7" />


### RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
