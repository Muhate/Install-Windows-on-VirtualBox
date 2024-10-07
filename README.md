# Create Windows server 2022 Virtual Machine on VirtualBox

### 1. Description

This project aims to demonstrate how to create a Windows server 2022 Virtual Machine on Oracle VirtualBox.

### 2. Objectives

- Set up a VM with Windows server 2022 Operating system.

### 3. Tools and Technologies Used

- **VirtualBox**: Used for creating virtual machines for the lab environment.
- **Windows server 2022**: Created as a VM.


### 4. Installation Steps
   
First, we need to download the ISO file from the Microsoft official webpage, so we go <a href="https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022">here</a> and click the **"Download the ISO"** hyperlink, shown below.

<p align="center">
  <img src="https://github.com/user-attachments/assets/685c3d6c-a1e9-4974-9419-d26c264516f5" alt="Download the windows ISO" width="500"/>
</p>

Another page will be opened, fill the form according to your details and click the **"Download Now"** button.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1ab24875-9d16-4b09-b4c4-3899fa2d789c" alt="Form to be filled" width="500"/>
</p>


   - **4.1. Create the VM on VirtualBox**

Open VirtualBox, then click Machine => New, to create a new VM.

<p align="center">
<img width="520" alt="VM creation on VirtualBox" src="https://github.com/user-attachments/assets/6bd9b8aa-9ccd-4043-a38e-0447c02f8f65">
</p>


Fill with the information of your choice, in this case the name is Windows Server 2022. Do not forget to select the option **"Skip Unattended Installation"** to prevent the VM to start before finishing our configurations.

<p align="center">
<img width="520" alt="VM name" src="https://github.com/user-attachments/assets/9f974b9b-c8af-4684-b9dd-420087079337">
</p>

Allocate enough memory and CPU and then click **"Finish"**

<p align="center">
<img width="520" alt="RAM and CPU" src="https://github.com/user-attachments/assets/580e9a85-f0c3-455a-8821-a529c0e7c1fc">
</p>

Make sure you select the VM and follow the steps indicated in the image below. In the end click the **"Star"** button.

<p align="center">
<img width="520" alt="Start VM" src="https://github.com/user-attachments/assets/0fa558d3-473e-47ea-b638-fdf92fcb2f2b">
</p>

Select language for the installation, the time and currency formats and the keyboard language, then click **"Next"**

<p align="center">
<img width="520" alt="Language configuration" src="https://github.com/user-attachments/assets/7fd26ac1-b919-4fe9-ac33-b96fa1f9c5bd">
</p>

Click **"Install now"** as shown below.

<p align="center">
<img width="520" alt="Install button" src="https://github.com/user-attachments/assets/b904c56e-6d13-4711-abe0-42bb8db1a85e">
</p>

select the OS to install and click **"Next"**. Here we selected **"Windows Server 2022 Standard Evaluation (Desktop Experience)"**.

<p align="center">
<img width="520" alt="OS selection" src="https://github.com/user-attachments/assets/16a4d9eb-a796-451a-9755-8a0b2c38579d">
</p>

Agree with the license terms and click **"Next"**.

<p align="center">
<img width="520" alt="License terms" src="https://github.com/user-attachments/assets/47edebbe-80c9-45c5-8351-809ee4d467a0">
</p>

Choose the type of installation, here we choose **"Custom: Install Microsoft Server Operating System only (advanced)"**, so click on it.

<p align="center">
<img width="520" alt="Type of installation" src="https://github.com/user-attachments/assets/d7f57adf-58ae-4664-a432-7a1e6dad1020">
</p>

In the next screen just click **"Next"**

<p align="center">
<img width="520" alt="where to install the OS" src="https://github.com/user-attachments/assets/c5779e32-f539-4358-8415-d85bc6c77cc4">
</p>

Finally click **"Reboot now"**

<p align="center">
<img width="520" alt="Reboot" src="https://github.com/user-attachments/assets/65ac004f-a90d-4642-af4e-5d4949fc9026">
</p>

Type and retype the password for the user **"Administrator"** and click **"Finish"**

<p align="center">
<img width="520" alt="Admin password" src="https://github.com/user-attachments/assets/d69018e9-6e47-4569-8511-667c4975453f">
</p>

Let us login to the VM, follow the steps indicated in the image down below.

<p align="center">
<img width="520" alt="Login" src="https://github.com/user-attachments/assets/c3a30c1a-eb0f-46e0-8161-06c572e77213">
</p>

Now we are going to enable the **"Copy and Paste"** from the guest to host and vice-versa.

<p align="center">
<img width="520" alt="Enable copy & paste" src="https://github.com/user-attachments/assets/32dcb5d9-8fc6-461e-bcec-7f3a98319109">
</p>

<p align="center">
<img width="520" alt="Enable copy & paste" src="https://github.com/user-attachments/assets/08fb7009-0582-40a3-bf38-4a47e1666269">
</p>

Now install the VirtualBox Guest Additions, follow the steps shown below. After those operations, the disk on number 3 will appear, double click it.

<p align="center">
<img width="520" alt="Guest Additions installation" src="https://github.com/user-attachments/assets/fc444874-5be3-4180-93b5-2aa2b2d144be">
</p>

Right click the file shown in the image and Run as administrator to install the VirtualBox Guest Additions.

<p align="center">
<img width="520" alt="Run the executable file" src="https://github.com/user-attachments/assets/adbc5f36-230b-4930-b6b0-96167765fedb">
</p>

Click **"Next"** to proceed with the installation.

<p align="center">
<img width="520" alt="Run the executable file" src="https://github.com/user-attachments/assets/e6c81ca1-760a-4fa3-91c5-3c50da975a2c">
</p>

Choose the folder where to install the guest additions and click **"Next"** to proceed.

<p align="center">
<img width="520" alt="Run the executable file" src="https://github.com/user-attachments/assets/691d7da2-54f8-4f35-9b81-713b8dc32faa">
</p>

Choose the components to install and click **"Install"** to proceed.

<p align="center">
<img width="520" alt="Run the executable file" src="https://github.com/user-attachments/assets/d7bee40f-5c82-41ea-8820-4c3f2a66af1e">
</p>

Select **"Reboot now"**. Here we choose to reboot later as we are going to make some other configurations.

<p align="center">
<img width="520" alt="Run the executable file" src="https://github.com/user-attachments/assets/7d5a8770-b372-41cd-80c9-f93fc6c2e99c">
</p>

### 5. **Conclusion**
   - This project successfully demonstrated the creation of a VM on VirtualBox with Windows Server 2022 operating system.

### 12. **Contact Information**
   - **Name**: Rogério Muhate
   - **Email**: rbmuhate@gmail.com
   - **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/rmuhate)
