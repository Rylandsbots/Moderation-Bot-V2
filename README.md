# Discord Bot Configuration

This repository contains the configuration file for a Discord bot. The configuration file is written in JSON format and includes various settings for the bot's functionality, such as welcome and leave messages, captcha verification, self-role menus, and various commands.

## Setup

To set up the bot, follow these steps:

1. Clone the repository or download the configuration file. - Repository: `git clone https://github.com/jared-jewitt/discord-bot-config.git`
2. Open the configuration file in a text editor.
3. Replace the placeholders with your own values, such as the bot token, client ID, server ID, and MySQL database credentials.
4. Save the configuration file.
5. Run the bot using the appropriate command or script, passing the configuration file as an argument.

## Configuration Options

The configuration file includes the following sections:

### Discord Bot Settings

- `token`: The bot's authentication token.
- `clientId`: The bot's client ID.
- `serverID`: The ID of the server where the bot will operate.
- `serverName`: The name of the server.

### MySQL Database

- `host`: The hostname or IP address of the MySQL server.
- `user`: The username for the MySQL database.
- `password`: The password for the MySQL database.
- `database`: The name of the MySQL database.

### Welcome Messages

- `enabled`: Whether welcome messages are enabled or not.
- `welcomeChannel`: The ID of the channel where welcome messages will be sent.
- `welcomeMessage`: The welcome message text.
- `joinrole`: The ID of the role to be assigned to new members.
- `aboutUS`: A brief description about your organization or server.
- `embedcolor`: The color of the embed message.

### Leave Messages

- `enabled`: Whether leave messages are enabled or not.
- `leaveChannel`: The ID of the channel where leave messages will be sent.
- `leaveMessage`: The leave message text.
- `embedcolor`: The color of the embed message.
- `enableImage`: Whether to include an image in the leave message or not.
- `leaveimage`: The URL of the image to be included in the leave message (if `enableImage` is set to `true`).

### Captcha Verification

- `enabled`: Whether captcha verification is enabled or not.
- `channelID`: The ID of the channel where captcha verification will take place.
- `RoleIDAssign`: The ID of the role to be assigned to users who pass the captcha verification.
- `logChannelID`: The ID of the channel where captcha verification logs will be sent.

### Self-Role Menus

- `enabled`: Whether self-role menus are enabled or not.
- `embedcolor`: The color of the embed message.
- `menuname`: The name of the self-role menu.
- `description`: The description of the self-role menu.
- `customid`: The custom ID of the self-role menu.
- `channelID`: The ID of the channel where the self-role menu will be displayed.
- `embedsend`: Whether to send the self-role menu as an embed message or not.
- `selfroles`: An array of self-roles, each with a `label` and `value` (role ID).

### Embed Settings

- `thumbnails`: The URL of the thumbnail image for embed messages.
- `footers.text`: The text to be displayed in the footer of embed messages.
- `footers.icon_url`: The URL of the icon to be displayed in the footer of embed messages.

### Command Settings

The configuration file includes settings for various bot commands, such as the invite command, magic 8-ball command, cat command, dog command, ISS command, nickname command, and truth or dare command. Each command section includes the following options:

- `ToggleFeature`: Whether the command is enabled or not.
- `channelLock`: Whether the command is restricted to a specific channel or not.
- `channelId`: The ID of the channel where the command can be used (if `channelLock` is set to `true`).
- `embedcolor`: The color of the embed message for the command.
- `ephemeral`: Whether the command response should be ephemeral (visible only to the user who invoked the command) or not.

Additional command-specific options may be included in the respective sections.

## Contributing

If you want to contribute to this project, feel free to submit pull requests or open issues for bug reports or feature requests.

## License

This project is licensed under the [MIT License](LICENSE).
