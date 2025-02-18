**Step 1: Download the iso image from the official site https://www.kali.org/get-kali/#kali-installer-images**

![Image](https://github.com/user-attachments/assets/f707939e-cc28-4262-95fe-1df34c12ded3)

**Step 2: Create a new vm using the downloaded iso image.<br>** 
      2.1 Use the folowintg settiings for vm  
      2.2 Select **Typical** configuration.**Next**      
![Image](https://github.com/user-attachments/assets/9ed1bc69-9686-4d32-9778-2f0aec55c400)
      2.3 Select **I will install the operating system later** . **Next**  
![Image](https://github.com/user-attachments/assets/07415f2a-17a8-468d-b93d-083c828e3e92)
      2.4 Select **Linux** as operating system and choose **Debian 11.x 64 bit**  as the version from the dropdown menu.**Next**
![Image](https://github.com/user-attachments/assets/87d2a0a0-3fae-4552-aa9c-d93110190226)
      2.5 Put the name of the machine as **initials_kali** and select thew location of the file .**Next**
![Image](https://github.com/user-attachments/assets/69bbfaee-92d1-490c-8935-5220d720a71a)
      2.6 Dedidcate **25 GB** for storage and select **Store virtual disk as a single file**. **Next**
![Image](https://github.com/user-attachments/assets/618cde82-880c-4a2c-8984-2dad9e0ec8b8)
      2.7 Select **customize hardware** .
![Image](https://github.com/user-attachments/assets/fb542b20-49be-41c4-a8f1-394c63c50662)
      2.8 Select **4GB memory** minimum. Select **Network** and choose **Bridged** as network connection .
![Image](https://github.com/user-attachments/assets/b1ba9391-b042-4928-9bcf-6f25a1909d1a)
      3.9 Select **New CD/DVD(SATA)** and select **Use iso image file**,**browse** and locate the iso image that you downloaded.**Close**      
![Image](https://github.com/user-attachments/assets/f6cb65f7-c2e8-4239-8db3-e5e10c0c6e82)
      3.1 **Finish**<br>
![Image](https://github.com/user-attachments/assets/25b33667-a2b8-493d-a239-3093b6d21feb)

**Step 3: Power on the virtual machine that was created.<br>** 
![Image](https://github.com/user-attachments/assets/c04ab5f7-ddf4-4765-a5db-010e1c055eca)

**Step 4: Setup the Kali linux .<br>** 
      4.1 Select **Graphical install** from the options.
![Image](https://github.com/user-attachments/assets/f73e42ba-5fd2-4b2d-bd97-7d580397f59b)
      4.2 Select the language as **English**.**Continue**
![Image](https://github.com/user-attachments/assets/9fe9b8ed-49ed-4426-8d86-b8d0f85b652a)
      4.3 Select your location.**Continue**
![Image](https://github.com/user-attachments/assets/ecfd78db-6707-45d5-804e-aa11a74824e6)
      4.4 Configure the keyboard as **American English**.**Continue**
![Image](https://github.com/user-attachments/assets/8fa89990-35f0-4bb8-b18b-47edbf85d55b)
      4.5 Load drivers from removable media, select **Yes**.**Continue**
![Image](https://github.com/user-attachments/assets/b2e1ab35-9caa-4072-9a5f-01f350c90843)
      4.6 Enter the hostname as **initials-kali**.**Continue**
![Image](https://github.com/user-attachments/assets/5a0bf8d7-f94c-464b-bca7-f65b377d4afa)
      4.7 Leave the doamin name empty and select **Continue**<br>
      4.8 Enter the password.**Continue**
![Image](https://github.com/user-attachments/assets/6e9eb317-bb46-4938-b275-01532415c8cf)
      4.9 Leave the HTTP proxy blank.**Continue**<br>
      5.0 Enter your **Full Name**.**Continue**
![Image](https://github.com/user-attachments/assets/a2bc9fc1-234f-4fee-9a14-61a11964231a)
      5.1 Enter the username and **Continue**
![Image](https://github.com/user-attachments/assets/7643b21c-eba7-4446-9d99-aa4067bf9e85)
      5.2 Enter the password.**Continue**
![Image](https://github.com/user-attachments/assets/a05a5482-7cb9-4f69-a89b-15d24b6ff43a)
      5.3 Configure the clock and **Continue**
![Image](https://github.com/user-attachments/assets/ee8c3f38-f159-4b3b-a335-9b0a8ca39394)
      5.4 Partition disk, Select **Guided-use entire disk.Continue**
![Image](https://github.com/user-attachments/assets/eb8477b9-0ef3-40ca-9f45-9d7643d412e9)
      5.5 On the next page leave as it is and  **Continue**
![Image](https://github.com/user-attachments/assets/edc31016-0695-4ba2-9af8-f761c1a2db43)
      5.6 Select the Partitioning as **All files in one partition.Continue**
![Image](https://github.com/user-attachments/assets/41ca1009-de41-40a2-a1bc-b79c73632873)
      5.7 Select **Finish Partitioning and write changes to disk .Continue**
![Image](https://github.com/user-attachments/assets/660333a0-08bd-41be-b6ca-04e25d485be2)
      5.8 Select **Yes** to changing the disk .**Continue**
![Image](https://github.com/user-attachments/assets/d8476aa8-dd21-4a36-a9d1-0e3f1d8513c7)
      5.9 Let the installation process run and select the options and **Continue**
![Image](https://github.com/user-attachments/assets/f4b18f95-16c9-40ba-9b10-e84aa64f1622)
      6.0 Select **Yes** to GRUB boot loader installation.**Continue**
![Image](https://github.com/user-attachments/assets/e6292944-3ffa-4654-9789-f5cadc4bd262)
      6.1 Select the location to install the GRUB loader and **Continue**
![Image](https://github.com/user-attachments/assets/81337db7-99d5-4b6f-be06-3cf9b48839de)
      6.2 **Continue** to reboot .
![Image](https://github.com/user-attachments/assets/ded585c3-9c86-42e9-88fc-eb7a388bcf8b)
      6.2 Now open the settings of the vm and then select **Use physical device.Ok**
![Image](https://github.com/user-attachments/assets/eeccdf67-5cdd-40a8-bbaf-09895d5e23b8)
**Step 5: Power on the vm and enter the credentials .<br>** 
![Image](https://github.com/user-attachments/assets/298cd211-0087-4a17-a183-044ca6db74ec)
**Step 6: Enter the credentials.You have succesfully setup the vm  .<br>** 
![Image](https://github.com/user-attachments/assets/381400b0-0bbc-4545-8b92-e3bf1b1f23d6)

