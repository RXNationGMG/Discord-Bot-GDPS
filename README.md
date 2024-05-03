# Discord Bot GDPS 

A Discord Bot GDPS for your Geometry Dash Private Server.

## ⚠️ Notice

**This repository is no longer up to date.** Please refer to [version 1.0.4](https://github.com/FamryAmri/Discord-Bot-GDPS/releases/tag/1.0.4) for the latest stable release.

## 🛠️ Setup Instructions

1. **Download and Extract:**
   ![...](https://github.com/FamryAmri/Discord-Bot-GDPS/assets/77547237/9d794639-cf92-4b65-b9ba-65383c4fd4ec)
   - Download this repository and extract the files.
   - Upload the `bot` folder/directory into your Geometry Dash Private Server to allow the bot to read files.

2. **Configure Bot:**
   ![...](https://github.com/FamryAmri/Discord-Bot-GDPS/assets/77547237/9f2ba97b-b4f3-47a2-b653-91439e0af3c1)
   - Setup [`botConfig.php`](https://github.com/FamryAmri/Discord-Bot-GDPS/blob/master/bot/botConfig.php) for emoji set.

3. **Create Discord Bot:**
   ![...](http://famrygd.5v.pl/totur/image1.png)
   ![...](http://famrygd.5v.pl/totur/image2.png)
   - Visit the Discord development portal and create a new application.
   - Customize your bot name and generate a bot token with admin permissions.

5. **Setup Bot Credentials:**
   ![...](http://famrygd.5v.pl/totur/image4.png)
   ![...](https://github.com/FamryAmri/Discord-Bot-GDPS/assets/77547237/c39de078-28fd-47d8-b372-475702d9ac6f)
   ![...](https://github.com/FamryAmri/Discord-Bot-GDPS/assets/77547237/b421dfdf-894d-447a-bdff-daec8fef7ada)
   - Edit `setup.json` and `.env` files in the `botfiles` folder.
   - Insert your bot token and [user ID](https://support.discordapp.com/hc/en-us/articles/360000291932).
   - Define your preferred bot prefix in `setup.json`.
   - Ensure your GPD host URL is correctly configured.

## 🚀 Hosting Options

### Hosting on Android (Termux)
1. Install Termux from the Termux Site.
2. Execute the following commands:
   ```bash
   pkg i nodejs
   cd /sdcard/your-path-folder/botfiles
   npm i
   node index.js
   ```

### Alternative Hosting Platforms

Considering the cessation of Heroku's free services, we recommend exploring alternative hosting platforms such as [Glitch](http://glitch.com) and [Repl.it](http://repl.it).
- Clone or import this repository to the platform of your choice.
- Utilize UptimeRobot to maintain the bot's online presence consistently.

## 📝 Credits

- [Cvolton](http://github.com/cvolton)
