# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212223040191
Name: Shanmuga Vasanth M
```
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
![Screenshot 2025-04-21 092131](https://github.com/user-attachments/assets/ed3e0cac-bed4-455c-b2e9-138bcb46a26c)

sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-21 092203](https://github.com/user-attachments/assets/8190bdb9-e380-4d68-9094-b877764f5299)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2025-04-21 092232](https://github.com/user-attachments/assets/edfed9c0-1c8a-410b-8c43-93d71ce56595)




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2025-04-21 092356](https://github.com/user-attachments/assets/50c6cd96-93f0-4d81-9542-30614f9a2afc)




It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2025-04-21 092417](https://github.com/user-attachments/assets/efe8a93d-71b1-42e3-9d72-4d738bd1cc11)



It shows the following screen in which the option Google can be selected:

![Screenshot 2025-04-21 092502](https://github.com/user-attachments/assets/b5d9c38c-1e5d-48da-bb2f-734c9a81e11a)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2025-04-21 092533](https://github.com/user-attachments/assets/377b9555-2a02-40e0-9d13-94e5233ec8aa)




In windows IE, on giving the url http://192.168.1.4, the fake Google page is displayed. The victim can enter the username and password

![Screenshot 2025-04-21 092725](https://github.com/user-attachments/assets/5594becf-ed88-45ee-8975-7dffbefe7ce7)



SET logs the information regarding the Google credentials:

![Screenshot 2025-04-21 092748](https://github.com/user-attachments/assets/7ef5a0b8-93e6-4c98-81c4-edf693d56b64)



SET logs the information in the xml file under /root/.set directory:

![380635070-eb860581-4b9f-4923-b762-13423fb56ee0](https://github.com/user-attachments/assets/0f376718-05ef-4e09-8150-0c867a83de9e)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
