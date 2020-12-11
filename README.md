# Rotom
> Rotom is a discord bot that allows you to create a Pokemon Go Discord Community with automated raids! Private raid channels, cross-server player profiles, party managment, notifications, and more!

## Getting Started

> **NOTE: Channel creation will be automated in future updates.**


> For now you need to enable developermode on discord to get the channel/category ids:
https://techswift.org/2020/09/17/how-to-enable-developer-mode-in-discord/

1. Create a category for active raids to be hosted under ( Active Raids )

![](https://i.imgur.com/IIcjSBj.png)

2. Create channels for raids to be hosted in.

![](https://i.imgur.com/1wQurLB.png)

3. Create a Reports Channel. (For user reports to be put in from `-report @user`)

4. Create a Logs Channel. (This is for rotoms error/raid logs)

5. Run the `-setup` command to add your server to the database.

6. Run `-setup auto` and answer the questions.

**PC:**:To get the ID of a channel, right click the channel/category and press copy ID.

**Phone:**:To get the ID of a channel, hold down on the channel/category and select copy ID.

# Commands
> All commands for rotom can also be found by typing `-help`. In addition each command of rotom has a help text that can be displayed by typing `?command`.
## User Commands

`-help` - Display the list of rotom commands.

`-acct` - Select your account. **Example:** `-acct 1`.

`-main` - sets your main pogo account **Example:** `-main Batmanpng`.

`-alt` - sets your alt pogo account **Example:** `-alt Batmanpng2`.

`-alt2` - sets your alt2 pogo account **Example:** `-alt2 Batmanpng3`.

`-show` - show your current accounts trainer code. **Example:** `-show`

`-lb` - show the global rotom raids leaderboard accrost all servers.

`-stats` - show your trainer stats!

`-report @user <reason>` - Report a user for bad hosting, or not joining raids.

## Raid Commands

`-host @pokemon <#invites> <TimeLeft>` - Host a pokemon raid. **Example:** `-host @Absol 5 15`.

`rehost <Optional Account #>` - Rehost your past raid, **can only be used in a raid channel.**

`-start` - start your raid, get a list of your partys in-game-names and invite them!. **can only be used in a raid channel.**

`-end` - end a successful raid **can only be used in a raid channel.**

`-add @user` - add a user to your party! **can only be outside a raid channel.**

`remove @user` - remove a user to your party!

`-leave` - leave a raid after 5 minutes! **can only be used in a raid channel.**

`-party` - Show your party, **can only be used in a raid channel.**





## Admin Commands

`-hostlock @user <optional reason>` - Lock a user from hosting raids in your server. **Example:** `-lock @HP`

`-lock @user <optional reason>` - Lock a user from interacting with rotom in your server. ( Joining and hosting raids ).

`-info @user` - View the information of a user. **Example:** `-info @HP`

`-fetch` - Fetch the latests pokemon raid bosses and create their roles.  **Currently under dev.**

`-setup` - Setup command for servers.

`-unhostlock @user` - unhostlock a user.

`-unlock @user` - unlock a user.

`-unraid @user` - Remove the in-raid value from a user.

`-vip` - Purchase/Check Vip Status.

## 
