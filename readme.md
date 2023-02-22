<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    Steam Query Bot for Discord Server Admins
</head>
<body>

External Resources: 

https://discord.com/developers/docs/intro


Steam Web API Documentation

https://steamcommunity.com/dev


Create a Discord App

https://discord.com/developers/docs/getting-started

https://discord.com/developers/applications

1) Navigate to the developer dashboard, then click New Application in the upper right corner
2) Enter a name for your app, then click Create (Once you create an app, you'll land on the General Overview page of the app's settings.)

Configuring bot

1) On the left hand sidebar click Bot, then the Add Bot button.

Note: Bot tokens are used to authorize API requests and carry all of your bot user’s permissions, making them highly sensitive. Make sure to never share your token or check it into any kind of version control.

2) Click Reset Token, and store the token somewhere safe

Adding scopes and permissions

Apps need approval from installing users to perform actions inside of Discord (like creating a slash command or adding emojis).

1) Click on OAuth2 in the left sidebar, then URL generator.

2) Add two scopes:

applications.commands lets your app create commands in guilds its installed bot is to enable your bot user. After you click bot, you can also add different user permissions to the bot. For now, just check Send Messages.





</body>
</html>
