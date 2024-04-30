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

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/6fd00aba-cd12-4ccb-ac26-56793f45360c)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/2a8e9465-8100-4beb-b4aa-e8d7e7373e3d)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/81d1e37b-072f-4e92-ba9f-3840ca398c59)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/15f82254-f1c8-4e41-b5c9-2eef14978d46)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/92306555-f3b4-42fd-821b-d8af1949c8fe)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/ac82be32-ef3c-40f7-9e1e-873310a0cfd0)

It shows the following screen in which the option Google can be selected:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/9f6abf78-7155-4eaa-a50a-9d3342187d6f)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/812c9bd1-55c9-409f-bd02-96b576711dc3)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/7507d4a6-8dff-4537-8651-17d9d39ea4e0)

SET logs the information regarding the Google credentials:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/a9099489-c7d4-4a6b-9484-79c5a37950cd)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:

![image](https://github.com/sathyaa22/creating-a-backdoor-with-SET/assets/140483368/2ad7682a-898b-4e03-9a19-af34d4eb8e85)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
