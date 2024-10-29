# PlasmaBot
## An Open-Source FIRST-Centered Discord Bot

Originally started in 2016, the PlasmaBot project seeks to develop a refined experience for members of the FIRST Robotics Community on Discord.

This is a full rewrite of the PlasmaBot codebase. While the bot's identity remains the same, certain features of the original bot may no longer be planned for this iteration or may be coming later.  This version of the bot contains the following plugins:
- **Activity Tracking**: Tracks user activity on a per-server basis _without logging message content_. Users can request statistics and graphs regarding their activity over a given period using various commands tied to period length.
- **AutoResponder**: Allows moderation to set Automatic Responses that are triggered via a Regular Expression match on message content.  Users of the server can then vote on whether or not to keep the message based on whether or not it is "useful" in context.  Once a message receives a configurable amount of votes or the original user votes against keeping it, the message will be deleted.
- **ModMail**: A FIRST Youth Protection Policy (YPP) compliant method of contacting and discussing moderation / server / organization issues with a specified panel of people. Users start "tickets" regarding a specific issue by pressing a Discord interaction button that then triggers a thread for them to discuss the issue with the mods and a seperate thread for the mods to respond and privately discuss the issue from their end. Mods respond using a slash command to allow for that private discussion.
- **Whisper**: A YPP compliant method of direct messaging users on a server.  Users trigger a command or use a context menu item to contact another user, who is notified via traditional DM from the bot.  They can then reply to that message directly from their DMs.  All messages within a message chain are logged for moderation in the initiating server, allowing moderators to ensure YPP guidelines are being followed.  Additionally, this plugin contains functionality to use Discord's Raid Prevention tools to disable standard DMs between users who are not already friends or share another server to help discourage use of unsafe or unrecommended communication channels.