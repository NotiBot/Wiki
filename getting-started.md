# Getting Started with Noti

## Getting started
### A step by step guide to get the Noti bot running on your Discord server.

Let's explore how to use Noti on your own server. We'll cover the fundamental steps, settings, best practices and later on tutorials for different use cases. While you can use built-in slash command via chat, this guide only covers setup via the online interface - the [Web Dashboard](https://notibot.app/dashboard).

## 1) Invite Noti to your Discord server

In order to use the Noti Discord bot and its features, you must first invite Noti to a server. You can invite the bot through the following ways:
  
  - **Noti's website**: Visit [https://notibot.app/](https://notibot.app/) and click on the "Invite Bot" link from the top right.
  - **Noti's dashboard**: In [Noti's dashboard](https://notibot.app/dashboard) - there will be a list of servers you can Noti to.
  - **Discord's App Directory**: Search for "Noti" or [click here](https://discord.com/application-directory/719310199944642753) and press the "Invite" button.
  - **Direct link**: Invite Noti through [this direct invite link](https://discord.com/oauth2/authorize?client_id=719310199944642753&permissions=286085598272&scope=bot+applications.commands).

{% hint style="info" %}
You may be **asked** to log in to your Discord account in order to add the bot and you also need to have the **Manage Server** permission on the server you want to add Noti to.
{% endhint %}

## 2) Checking role hierarchy (important!)

{% hint style="warning" %}
This step is essential if you use any role related feature with Noti, otherwise you will run into permission issues due to Discord's permission structure.
{% endhint %}

The next thing to do after inviting Noti is to check if Noti has sufficient permissions and is hierarchically arranged correctly. 
  1. Open your **server settings**. Navigate to **Roles** -> look for the bot role "Noti". (This role was automatically created after adding the bot and should be at the bottom of the list)
  2. Move the role above any other role which should be managed by Noti and a user could have while interacting with the bot.
     * If you are not sure which roles Noti will manage, it is recommended to drag this role to the top of the list.
    
## 3) Getting to know the dashboard

The dashboard is a website that allows you to fully manage Noti through a website. All features can be managed via this interface, while not all features can be set up using commands due to their complexity.

> Open [https://notibot.app/dashboard](https://notibot.app/dashboard) in your web browser and log in with your Discord account. Choose your server and start exploring all features to ensure you are comfortable with it.

{% hint style="info" %}
The dashboard is currently not optimized for mobile devices - if possible, use a PC or enable desktop mode on your mobile device.
{% endhint %}

