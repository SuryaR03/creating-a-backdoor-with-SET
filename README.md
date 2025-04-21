# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![Screenshot 2025-04-21 112838](https://github.com/user-attachments/assets/91d626ea-7bce-4431-a304-2fd638917936)

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-21 112916](https://github.com/user-attachments/assets/931116fa-f459-4505-9b5b-ecc35b3524c6)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot 2025-04-21 112929](https://github.com/user-attachments/assets/40076293-cfd1-4ebd-99c8-71b5909ba73d)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![Screenshot 2025-04-21 112946](https://github.com/user-attachments/assets/331d26be-7be9-415f-a46a-3b264cac56cc)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![Screenshot 2025-04-21 113005](https://github.com/user-attachments/assets/3fd76b4d-3274-4c91-ae50-18c1024a0cd7)

It shows the following screen in which the option Google can be selected:


![Screenshot 2025-04-21 113034](https://github.com/user-attachments/assets/d75763b9-e39b-4407-856c-99d18413c11e)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2025-04-21 113034(1)](https://github.com/user-attachments/assets/b4bc3b4b-cf1f-4dba-b429-f88088586bc5)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![Screenshot 2025-04-21 112714](https://github.com/user-attachments/assets/85ef3842-61dd-49c7-adfe-05b71290fd91)

SET logs the information regarding the Google credentials:
![Screenshot 2025-04-21 113034(1)](https://github.com/user-attachments/assets/06318da7-18eb-43a8-9b63-76f34ed4a1d8)

SET logs the information in the xml file under /root/.set directory:








## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
