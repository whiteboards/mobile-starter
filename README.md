# mobile-starter

[![Join the chat at https://gitter.im/whiteboards/mobile-starter](https://badges.gitter.im/whiteboards/mobile-starter.svg)](https://gitter.im/whiteboards/mobile-starter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A set of guidelines to work with the POC projects.

## What? Why?
To compare and contrast technologies. You can use whatever technology you want, but it must a mobile application. 

Example applications:
- Chat - **Recommended**
  - A chat application should be structured around users.
  - Group chats should be secondary, not primary.
  - The device should hold at least *some* of the recent messages locally for a form of history.
  - It should be realtime
- TODO list
- Notes
- Timer and alarms
- Reminders 
- Contact list

## Requirements
All POC should meet the requirements on this list.
- [ ] Local data storage
- [ ] "native" feel, this can be accomplished with a native implementation, or something like `react-native`
- [ ] Data input (it can't be read-only)
- **Must be submitted by August 16, 2017. Submit with PR** It is a short timeframe, but this is on purpose.
 - Make a PR on this readme and add your application repo to the list of `POC`'s if it isn't a fork of this repository. 

## Optional Checkboxes
You don't have to have these things, but it would be cool if you did.
- [ ] Realtime data sync - Your application talks to an api server to backup the data you input, without the user having to initiate it.
- [ ] Cross-platform - Your application works on more than just android.
- [ ] Data encryption - Whatever data your are storing or sending, only the user and its intended target can read it.
- [ ] Works fully offline - Obviously this doesn't make sense for some applications, like chat, but if you are building a todo list, it should work without an internet connection.
- [ ] Users - Data can be accessed by a user on another device if they provide correct credentials. 
- [ ] peer to peer - Data never has to touch your server to reach users, if they don't want it to. Ideal for chat.
- [ ] Single sign-in - If your application requires authentication, let a user do it once and be done, or use something like `touch-id`. Don't make them work for it.


## Ready, set, go.
Good luck.


## Known P.O.C. Projects
- None yet!
