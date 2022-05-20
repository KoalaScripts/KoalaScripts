# Welcome to the KoalaBot Documentation ! 
![KoalaBot](/Docs/Koala%20Robot%205%202021.png)

The KoalaBot is a simple to use discord bot created with the mean purpose to create and host Runescape events. 


## 1. Installation

Surf to the installation link and follow the instructions to add the bot to the discord server. 
[Installation Link](https://discord.com/api/oauth2/authorize?client_id=878985424419307570&permissions=534723951680&scope=bot%20applications.commands)

## 2. Initial Setup

By default the Koalabot will create events and place the name of the event as the header. 
If you wish to have this name changed by a @group please use the /add_rolleto_boss. (to find more info about the command check the commands bellow)

## 3. Command info

- [x] **/add_roleto_boss**

The command allows you to add a @role to be assigned to a specific boss. This group will be shouted at upon event creation

##### Parameters
- boss : Select the boss you wish to add a role to shout upon creation
- role : Select the role you wish to be shouted

- [x] **/createevent**

This command allows anyone to start an event. 

##### Parameters
- boss : Select the boss you wish to host an event for
- starttime : specify the start time of the event . This needs to be in format hh:mm !
- date : specify the date you wish the event to occur on. This needs to be in format dd/mm/yyyy
- description : this is an optional parameter, provide this with a text you wish to add in the footer of the event. 

##### Signup for an event

To signup for an event click any button of the role you wish to do.

##### leave an event

To remove your signup click the button of the role you signed up for once again. 

##### Starting the event 

To start the event press the finalise button. 
You will now recieve a popup with a list of roles and the names of the people that signed up for the role. 
Remove or add members for each role . Each member needs to be seperated by a **,**

- [x] **/createevent_hosts**

This command is meant if you wish certain people (hosts) to create and finalise the events. 
Make sure you specify the role of the events in the /add_hostrole command ! Otherwise no one will be able to finalise the events.

##### Parameters
- boss : Select the boss you wish to host an event for
- host : The host of the event this person will get a ping 30 minutes in advance.
- Channel : Select the channel you wish the event to be posted in
- starttime : specify the start time of the event . This needs to be in format hh:mm !
- date : specify the date you wish the event to occur on. This needs to be in format dd/mm/yyyy
- description : this is an optional parameter, provide this with a text you wish to add in the footer of the event. 

##### Signup for an event

To signup for an event click any button of the role you wish to do.

##### leave an event

To remove your signup click the button of the role you signed up for once again. 

##### Starting the event 

To start the event press the finalise button. 
You will now recieve a popup with a list of roles and the names of the people that signed up for the role. 
Remove or add members for each role . Each member needs to be seperated by a **,**

The hosted events will be automaticly cleaned up by the bot 15minutes after the event. 

- [x] **/add_hostrole**

Add the role of the hosts you wish to be able to Finalise events. 

##### Parameters

- Role : Role you wish to have the rights. 