# Thor.js
![Thor](https://user-images.githubusercontent.com/90670265/133360481-f75f35cf-33b4-46cf-bff4-b2dc256f07ef.png)

A better fun thor bot but with lesser moderation commands.Can be made by one 

# Making

Make sure you’re logged on to the Discord website.

Navigate to the application page(https://discord.com/developers/applications)

![image](https://user-images.githubusercontent.com/90670265/133360879-f94232e8-0d9e-4031-9639-5731deded30b.png)

Click on the “New Application” button.

The new application button.
Give the application a name and click “Create”.
![image](https://user-images.githubusercontent.com/90670265/133360911-40d3dfe4-70aa-4903-aecc-dcdf887a2c19.png)


The new application form filled in.
Create a Bot User by navigating to the “Bot” tab and clicking “Add Bot”.

Click “Yes, do it!” to continue.
![image](https://user-images.githubusercontent.com/90670265/133360930-8f17f348-d174-4ce8-baa3-e3dcad526149.png)


The Add Bot button.
Make sure that Public Bot is ticked if you want others to invite your bot.

You should also make sure that Require OAuth2 Code Grant is unchecked unless you are developing a service that needs it. If you’re unsure, then leave it unchecked.
![image](https://user-images.githubusercontent.com/90670265/133360961-962646db-c596-450c-a481-51ce59bf9186.png)


How the Bot User options should look like for most people.
Copy the token using the “Copy” button.

This is not the Client Secret at the General Information page.


It should be worth noting that this token is essentially your bot’s password. You should never share this to someone else. In doing so, someone can log in to your bot and do malicious things, such as leaving servers, ban all members inside a server, or pinging everyone maliciously.

The possibilities are endless, so do not share this token.

If you accidentally leaked your token, click the “Regenerate” button as soon as possible. This revokes your old token and re-generates a new one. Now you need to use the new token to login.


Inviting the bot:
So you’ve made a Bot User but it’s not actually in any server.

If you want to invite your bot you must create an invite URL for it.

Make sure you’re logged on to the Discord website.

Navigate to the application page

Click on your bot’s page.

Go to the “OAuth2” tab.

How the OAuth2 page should look like.
Tick the “bot” checkbox under “scopes”.

The scopes checkbox with "bot" ticked.
Tick the permissions required for your bot to function under “Bot Permissions”.

Please be aware of the consequences of requiring your bot to have the “Administrator” permission.

Bot owners must have 2FA enabled for certain actions and permissions when added in servers that have Server-Wide 2FA enabled. Check the 2FA support page for more information.

The permission checkboxes with some permissions checked.
Now the resulting URL can be used to add your bot to a server. Copy and paste the URL into your browser, choose a server to invite the bot to, and click “Authorize”.

Good job your bot is done!


# Now time for making it run



