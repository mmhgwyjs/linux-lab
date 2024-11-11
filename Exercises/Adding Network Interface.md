Adding Network Interface

ip a 
- to check the available network interfaces

  ![image](https://github.com/user-attachments/assets/d73ec222-41ec-4917-9a44-7b38a3c988d2)

add new interface in VMware
- Right click the VM > Settings > Add > Select Network Adapter 

- ![image](https://github.com/user-attachments/assets/171d7cfc-da3b-48c5-8e7b-3dcc16c5eb03)

- Set to NAT for Internet access
  
- ![image](https://github.com/user-attachments/assets/118a2b20-f06a-4419-ad4c-5c777db7907b)


check the available net interface in the server

- ip a
  
  ![image](https://github.com/user-attachments/assets/cf8c0254-c5b7-4fcd-b6a3-434c21c5cbaa)

  ens32 is now added

Configure ens32 interface

sudo nano /etc/netplan/01-netcfg.yaml 

add an entry for the new interface, enable the dhcp
![image](https://github.com/user-attachments/assets/b18f0828-7839-4d97-985d-3a0499709ada)

sudo netplan apply > to apply the changes

![image](https://github.com/user-attachments/assets/5c89cf9d-f056-4d9f-9060-ebccad501b33)

ip a again to check the interfaces, notice that the ens32 is now in UP state

test the connection

![image](https://github.com/user-attachments/assets/174b2cce-b4d9-4d22-912a-d6f8ba5f25cf)

