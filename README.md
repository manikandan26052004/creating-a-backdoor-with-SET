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

![325464250-ef7b25b6-a477-4153-8066-5df532c07688](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/d056dc7c-7307-42f0-a6dd-19e4c830d5fa)

image It displays the following menu and select 2 for Website Attack Vectors: 

![325464403-cf29526b-3edc-4f4d-afa4-27926c2f1f24](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/ab41656f-18d9-4a8b-b179-887a5f1b6b72)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 

![325464403-cf29526b-3edc-4f4d-afa4-27926c2f1f24](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/204a2b45-6253-47fd-99da-32c2090c37b0)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![325464498-017d7cc5-e8bf-4bbf-a989-a98446ed662a](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/fc41bc9a-0360-4695-b65c-c8f77904d161)

It shows the following screen in which the ip address of the attacker need to be given which is the default value: 

![325464540-12696ddd-643e-4d84-ad46-51ca12acc8b7](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/9a9690c0-3ae9-48be-b0ea-e0b64999cbae)

It shows the following screen in which the option Google can be selected: 

![325464570-847305a1-96a5-40c0-82b7-9618558faeee](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/bd63cbfa-2b24-4bf8-9d68-c173335cf232)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![325464610-e03cbefa-1ed1-4158-86e6-4ac20056236a](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/06b3a571-152d-46be-8c63-d412eb29e676)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![325464661-3d4153f4-67e6-408f-898f-b7f636c970cc](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/a0079027-a94e-490d-8319-a5f3d57ed452)

SET logs the information regarding the Google credentials: 

![325464702-0d07b841-bc07-40cd-9bd7-f79aed210989](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/6499c898-a6e0-45d0-93e0-ee4f8759a6a3)

SET logs the information in the xml file under /root/.set directory: 

![325464750-a9160ebe-7b63-45f6-a059-f59375153548](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/2dc1b214-a872-4c81-a1b1-a869419bf47d)

![325464750-a9160ebe-7b63-45f6-a059-f59375153548](https://github.com/manikandan26052004/creating-a-backdoor-with-SET/assets/121999845/35287f69-6ca3-428c-8c7b-1fae5d566f0a)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
