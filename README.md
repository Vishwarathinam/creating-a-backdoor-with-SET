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

## OUTPUT:
![s1](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/83788c1e-18ba-418a-a2e8-55587253b435)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![s2](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/3489fc27-9cae-4cc8-89d6-9b2af97e1e04)


It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![s3](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/45166121-f033-4e4f-aa61-50654dcb1eae)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![s4](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/e9b2b2e7-4f56-46cb-9962-123f9c2a420d)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![s5](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/5bf03e5e-fc41-4a74-a00f-e6e82a82269c)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![s6](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/15f39ea5-c10b-44b7-ae6f-76d404a813d3)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![s7](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/bdc3e916-7914-4095-8fa6-b7afbf44b790)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![s8](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/5f25f0ff-bf43-41b8-abdb-c3238165ecc2)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![s9](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/76ab4183-8751-40e6-94f9-b9bf6f1cb7c5)


SET logs the information regarding the Google credentials:

## OUTPUT:
![s10](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/6bd33506-a2c2-457c-978b-8351984cea97)


SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![s11](https://github.com/Vishwarathinam/creating-a-backdoor-with-SET/assets/95266350/f2020983-d3df-4219-804f-3a4549b5d27d)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
