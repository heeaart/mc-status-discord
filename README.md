**This project uses MSC API ([mcstatus.io](https://mcstatus.io)) for getting status of Minecraft servers.**

## REQUIREMENTS
- **Need to install:**
    - [Node.js](https://nodejs.org/en/about) v16.9.0 or higher *([download here](https://nodejs.org/en/download))*
    - [NPM](https://docs.npmjs.com/about-npm) (automatically installs with Node.js)
- **Recommended to:**
    - Install IDE for editing files ([Visual Studio Code](https://code.visualstudio.com/) recommended)
- **How to use?**
    1. Edit the [`config.js`](config.js) and [`data.json`](data.json) files
    2. Use the command `npm install` before running to install all required dependencies (or use *"install-cmd"* in the [`package.json`](package.json) file)
    3. Use `npm start` or `node index.js` to run the project

## WHAT CAN THIS BOT DO?

- **Fully customizable [config](config.js)**
- Working **commands** with **custom prefix** + their **[slash commands]((https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ))**
    - `help` command for getting the help menu (list of all user-available commands)
    - `ip` command for getting the IP address of the server
    - `list` command for getting an actual list of online players now
    - `status` command for getting a simple and clear overview of the server
    - `version` command for getting the Minecraft version of the server
    - `vote` command for getting vote link for voting for server on Minecraft server list
- **Auto updating bot's status** with online and max players (setup in the config with variables)

## TODO

- [ ] Send custom embed message command
- [ ] Send a custom message/announcement command
- [ ] Better test command variables (more process info - like uptime)
- [ ] Poll/Voting command (simple or with more options)
- [x] <s>Auto changing statusCH message</s>
- [x] <s>Status command</s>
- [x] <s>IP address command</s>
- [x] <s>Minecraft version command</s>
- [x] <s>Player list command</s>
- [x] <s>Vote link command</s>
- [x] <s>Poll/Voting channel with reactions</s>
- [x] <s>Slash commands</s>
- [x] <s>Installation with repl.it</s>
- [x] <s>More text languages (or custom)</s>
- [x] <s>Bot status (activity) for players online number</s>
- [x] <s>Get invite link on bot start (available option in config)</s>
- [x] <s>Help command with all commands listing</s>#   m c - s t a t u s - d i s c o r d 
 
 
