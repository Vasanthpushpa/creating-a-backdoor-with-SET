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

![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/a13bd43d-8d45-4a92-a4c0-ff2967f1c720)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/df3220b8-4067-4d0e-822a-e22a64889d58)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/592297a3-b178-4563-a448-a372968a255a)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/227c207f-8dc9-473b-a274-4928955e7806)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/bc1ce0d8-4be7-43ae-bfb2-93771f6e85b6)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/6f2a3611-d20f-42c5-bd23-4ddaf3f1393b)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/475a206e-ff47-46f1-b897-5e34e2e586a2)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/93e70026-c1e3-4697-b7f6-1a99922d42ea)

SET logs the information regarding the Google credentials:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/ce4a0769-f4c3-4430-8f0f-24f24a15305c)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/SivaramakrishnanBaskar/creating-a-backdoor-with-SET/assets/119476322/f68f1b7e-705b-4688-b79b-2d3b6f2a4b1a)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
