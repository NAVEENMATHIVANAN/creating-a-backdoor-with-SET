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

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/6165d98d-6153-4406-b3bb-2a861c884ab5)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/c9b883fd-3c16-4428-b7cb-c620aa652b0f)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/0ad0571e-5f33-4df7-ae13-16aede429ed9)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/9527df42-0250-411e-b732-fd61f75e80a8)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/6c022c51-df90-4b16-aeec-f0d3b0d1521e)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/7388898e-9b05-408b-9ab6-c33b9f9dcd60)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/8948d6c9-2186-4bce-8137-8d1a147911a8)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/a52522cf-e742-4552-b72c-eff16ba836e8)


SET logs the information regarding the Google credentials:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/0c2257a8-21bc-409b-8733-b839dc85e13b)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/NAVEENMATHIVANAN/creating-a-backdoor-with-SET/assets/119394582/a829401b-fd83-489c-9d20-2bf58ee3ca38)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
