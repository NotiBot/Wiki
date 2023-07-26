# Setup Clips to Discord with Noti

**Signup and Connect with KickBot**:

* To use the Clips feature, you need to sign up for KickBot, which is a partner service for managing clips.
* Go to [http://kickbot.app](http://kickbot.app/) and create an account or log in if you already have one.
* Link your KickBot account with your Kick.com account if you haven't done so already.

**Accessing the Clips Command in KickBot**:

* Once you've linked your accounts, log in to KickBot.
* In the KickBot dashboard, navigate to the "Interactions" section.
* From the "Interactions" section, locate and click on the "!clips command", which is usually found as a subcategory under "Interactions."
  * For additional questions visit the [KickBot Wiki](https://docs.kickbot.app/dashboard/interactions/clip-command).

**Enable the !clip Command**:

* In the "!clips" command section, ensure that the "!clip" command is enabled. If it's not enabled by default, enable it.

**Return to Discord**:

* Head back to your Discord server where you invited Noti Bot.

**Run the /setup Command**:

* In any channel where Noti Bot has permission to interact, type the following command to set up the KickBot service:/setup service kick (kick.com username)Replace `(kick.com username)` with your actual Kick.com username. For example:/setup service kick yourkickuser

**Choose the Clip Channel (if prompted)**:

* After sending the /setup command, Noti Bot might prompt you to select the "Clip" option from the list of available services. Hit "Tab" to auto-complete the option or select it manually.
* If the bot asks you to provide a channel for posting clips, mention the channel using the "#" symbol. For example, if you want the clips to be posted in a channel called "#awesome-clips," you should type:/setup service kick mykickuser clip channel #awesome-clips
* Once you've typed the command correctly and specified the channel (if necessary), send the message.

Congratulations! You have now successfully set up the "Clips to Discord" feature with Noti Bot and KickBot. From now on, whenever you use the "!clip" command in KickBot, the clips will be shared in the specified channel (if you provided one) on your Discord server.
