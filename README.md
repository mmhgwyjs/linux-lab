# Linux Lab

> Please note that this project is ongoing and is meant solely for learning purposes. Your feedback would be greatly appreciated, as I am using this opportunity to learn.

## Objective

To set up a Linux machine and practice essential tasks such as user management, networking, web and database services, file sharing, monitoring, and security, along with backup and recovery.

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

> For this guide, we will install the user-friendly `Ubuntu`, specifically the [desktop version](https://ubuntu.com/download/desktop). If you prefer `Kali`, you can refer to this [guide](https://github.com/mmhgwyjs/pentest-lab).

***3. Creating the virtual machines.***

> I use VMware Workstation for this, but the same concept can be applied to VirtualBox.

- Go to `File` then select `New Virtual Machine`.

  ![image](https://github.com/mmhgwyjs/malware-analysis-lab/assets/159692853/22ab3330-bc2d-43ff-9d8f-ff34d7bde957)

- Select `Typical`. Under `Installer disc image file (ISO)`, locate your downloaded Ubuntu ISO. Then proceed to `Easy Install`.
  
  ![image](https://github.com/user-attachments/assets/2860b6cb-44b3-4dce-bea6-8e0534ead812)

- For the disk size and hardware settings, you can adjust them according to your preferences.

- Wait for it to boot up.

  ![image](https://github.com/user-attachments/assets/ffed5a80-c8a5-48ff-8c90-67c3d5f5c8a5)

- Complete the installation by following the straightforward GUI steps with the default settings.

  ![image](https://github.com/user-attachments/assets/750a991e-c0a1-4ea7-81ed-8fab57af3648)

- Restart the machine afterward.

  ![image](https://github.com/user-attachments/assets/376492d1-2ecd-4f65-9972-25a9d72292ac)

## Additional Configurations 

***1. Update the system.***

   - Using `Software Updater` app.
   
     ![image](https://github.com/user-attachments/assets/4e9da03e-3cf9-41d7-a092-8d7282ba5d8e)

     > Here is an example of a pop-up that appears after logging in.

   - We can also update Ubuntu via the terminal by typing `sudo apt update` followed by `sudo apt upgrade`.
   
     ![image](https://github.com/user-attachments/assets/5e03ded3-ece7-4261-9679-15f22d1ee2c1)

     > `sudo apt update`

     ![image](https://github.com/user-attachments/assets/0d6a07ee-2935-43bc-aeb7-ce195ca7d6b7)

     > `sudo apt upgrade`

> You can view the official installation guide for Ubuntu [here](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview).


#### ***Excellent work! Our Ubuntu Desktop is now set up and ready. Let’s proceed with the practical exercises outlined below.***

## Lab Exercises

- Coming soon



