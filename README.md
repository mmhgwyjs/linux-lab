# Linux Lab

> Please note that this project is ongoing and is meant solely for learning purposes. Your feedback would be greatly appreciated, as I am using this opportunity to learn.

## Objective

To set up a Linux server and practice essential tasks such as user management, networking, web and database services, file sharing, monitoring, and security, along with backup and recovery.

## Initial Setup

***1. Installing hypervisor.***
   
- You can use either VMware Workstation or VirtualBox, based on your preference. More details [here](https://github.com/mmhgwyjs/homelab?tab=readme-ov-file#hypervisor).

***2. Getting the Linux Distribution ISO.***

- There are many Linux distributions available, each with its own strengths and features. To find the one that best suits your needs, consider doing some research. Here are a few of the most popular distributions:

  - **[Arch](https://archlinux.org/download/)**: Known for its flexibility and customization.
  - **[Debian](https://www.debian.org/download)**: Valued for its stability and extensive software repository.
  - **[Kali](https://www.kali.org/get-kali/#kali-platforms)**: Specialized in security and penetration testing.
  - **[RHEL](https://developers.redhat.com/products/rhel/download)**: Red Hat Enterprise Linux, favored in enterprise environments for its support and reliability.
  - **[Ubuntu](https://ubuntu.com/download/server)**: Popular for its user-friendliness and strong community support.

> For this guide, we will install the user-friendly `Ubuntu`, specifically the [desktop version](https://ubuntu.com/download/desktop). If you prefer `Kali`, you can refer to this [guide](https://github.com/mmhgwyjs/pentest-lab) instead.

***4. Creating the virtual machines.***

> I use VMware Workstation for this, but the same concept can be applied to VirtualBox.

- Go to `File` then select `New Virtual Machine`.

  

- Select `Typical`. Under `Installer disc image file (ISO)`, locate your downloaded Ubuntu ISO. Then proceed to `Easy Install`.
  
  


- For the disk size and hardware settings, you can adjust them according to your preferences.

  ![image](https://github.com/user-attachments/assets/ec6258b5-18cd-404c-a341-e361f678ba48)
