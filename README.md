# Engramify v1.0

Engramify is a Windows desktop console for Discord bots. It includes a sample workspace you can explore before connecting a bot.

[Download the Windows installer](https://github.com/mkk126/engramify-public/releases)

## Install and connect

1. On Windows 10 or 11 x64, open **Engramify-1.0.0-Windows-x64-Setup.exe**. The installer includes the desktop runtime.
2. Open **Engramify** from Start or the desktop shortcut. Choose **Explore sample workspace** to try the interface offline.
3. To connect a bot, paste its token into the masked field inside Engramify. Invite the bot to the servers you want to manage. Enable **Message Content Intent** in the Discord Developer Portal to read ordinary server message text, or clear **Read message content** when connecting with limited visibility. [Discord Developer Portal](https://discord.com/developers/applications)

## What you can do

- Browse servers and channels, read live messages, search history, jump to pins, and open DMs, threads, and forum posts.
- Send messages, replies, attachments, and reactions. Edit or delete the bot’s own messages and manage pins where permitted.
- Update the bot’s profile and presence. Use permission-checked server moderation and **Diagnostics** to see what the bot can access.
- Join server voice with push-to-talk, input and output selection, and per-person volume.

Closing the window keeps the bot connected in the Windows notification area. Choose **Disconnect** to clear its token, or right-click the tray icon and choose **Quit Engramify**. The token stays in memory while connected.

## Download verification

**SHA-256 for `Engramify-1.0.0-Windows-x64-Setup.exe`**

```text
64cc7578afbdad93692867db6f44b87a0692ae3c1702f13ca924a01724ec1609
```

Windows may show an unknown publisher prompt for an unsigned installer. Third-party notices are included with the installed app.
