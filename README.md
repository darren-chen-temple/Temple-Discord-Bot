# Temple Discord Bot
###### proposed by Darren Chen

## Project Abstract
A Temple University Discord bot that delivers Temple-related news and TUAlerts right to your local Discord server! 
Just add it to a Discord server, and any user can request useful information like upcoming events, recent @TempleUniv 
tweets, or even track the active COVID-19 cases on campus! It even delivers TUAlerts, so you can get all the necessary 
Temple-related information in one place!

### Diagram
![Temple Discord Bot UML Diagram](https://user-images.githubusercontent.com/70285006/109034182-61538400-7695-11eb-9173-61587b104cf4.png)

## Project Relevance
This project will demonstrate the practical application of Object Oriented Design (if done in Java), and due to the
nature of this project needing to pull information from various sources, will necessarily involve project management and
version control via Github, which will allow the team working on this to branch the various tasks, test stable builds,
and track issues. While the bot is not a modification of an existing open-source program (it could be, if I can manage
to locate and contact the author of the Discord bot that inspired this project proposal), it handles a variety of tasks
that could be split up among the members of the small team that will be working on said project. These goals are
relevant and important to this project in they will provide practical experience in using modern software development 
tools such as Github, as well as in working in small teams on an open-source program inspired by a pre-existing, useful,
and recent project.

## Conceptual Design
Since most students are stuck at home attending online classes, glued to their computers, and constantly using Discord, 
why not have useful information more readily available without the need to pick up your phone or switch websites or apps?
The bot will have access to multiple sources (Temple University Twitter, Owl Connect, Temple COVID-19 Dashboard) and be
able to deliver relevant and useful information upon request from any Discord user in a server where the bot is active,
and will automatically deliver TUAlerts when they appear. Thus, the bot will be able to listen to messages
delivered in a Discord server, and respond accordingly when a user specifically requests the bot to take action.

## Background
This project was inspired by another Temple-related Discord bot, Temple Covid Cases, that would provide updates on
active COVID-19 cases on campus. The bot was floating around for a while, but now (unfortunately!) appears to be
inactive. While I have yet to identify the bot's creator or locate the original bot online, this project seeks to be the 
spiritual successor to the Temple Covid Cases bot, complete with some new additional features!

#### _Building_
- Basic Overview for Creating a Discord Bot in Java: https://www.writebots.com/how-to-make-a-discord-bot/#Java_Coding_Your_Discord_Bot_in_a_Robust_Popular_Language
- Using IntelliJ IDE and including the library/wrapper JavaCord or Discord4J (respectively) OR this Java Discord API created by the folks at https://github.com/DV8FromTheWorld/JDA 
- Alternatively, can be done in Python: https://realpython.com/how-to-make-a-discord-bot-python/#how-to-make-a-discord-bot-in-the-developer-portal
- Essentially, creating a Discord developer account, and using the discord.py (Discord's Python API)


#### _Running_
- Will have a main, but will also necessarily have to be tested via Discord by issuing pings and letting the bot respond
to user input
  

## Notes and Suggested Additional Features:
- menu (a !help function)
- information on registration dates, Temple bulletin
- links to contact info, etc

## Whiteboard Presentation Slide
![Temple Discord Bot Whiteboard Presentation](https://user-images.githubusercontent.com/70285006/109034677-e2128000-7695-11eb-8358-90e15351748e.png)
