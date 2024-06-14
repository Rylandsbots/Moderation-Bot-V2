# Moderation Bot V2 - Pterodactyl Installation

This guide will walk you through the installation process of the Moderation Bot V2 on a Pterodactyl panel.

## Prerequisites

- Access to a Pterodactyl panel
- Git (optional, if cloning the repository)

## Installation

1. **Create a Server on Your Panel or Have Your Hosting Provider Do So**
   - Log in to your Pterodactyl panel
   - Create a new server or have your hosting provider create one for you

2. **Set up the Server**
   - Go to the server configuration
   - Set up one database for the bot
   - Set your desired RAM and CPU resources
   - Select the Docker Image: `Nodejs 21`
   - Set the Main File: `src/index.js`
   - Set the Git Repository URL: `Coming Soon` (once the repository is available)

3. **Clone the Repository or Download the Configuration File**
   - Once the repository is available, clone it using: `git clone <repository_url>`
   - Alternatively, download the configuration file from the repository

4. **Open the Configuration File and Replace Placeholders**
   - Open the configuration file in a text editor
   - Replace the placeholders with your own values, such as the bot token, client ID, server ID, and MySQL database credentials
   - Save the configuration file

5. **Run the Bot**
   - In the Pterodactyl panel, navigate to the server console
   - Run the bot using the appropriate command or script, passing the configuration file as an argument

## Configuration

The configuration file includes the following sections:

- **Discord Bot Settings**: Token, client ID, server ID, server name
- **MySQL Database**: Host, user, password, database name
- **Welcome Messages**: Enabled, welcome channel, welcome message, join role, about us, embed color
- **Leave Messages**: Enabled, leave channel, leave message, embed color, enable image, leave image
- **Captcha Verification**: Enabled, channel ID, role ID to assign, log channel ID
- **Self-Role Menus**: Enabled, embed color, menu name, description, custom ID, channel ID, embed send, self-roles
- **Embed Settings**: Thumbnails, footers (text and icon URL)
- **Command Settings**: Toggle feature, channel lock, channel ID, embed color, ephemeral (for various commands like invite, magic 8-ball, cat, dog, ISS, nickname, truth or dare)

Make sure to replace the placeholders with your own values and configure the bot according to your needs.

## Running the Bot

Once the configuration is complete, the bot should be up and running on your Pterodactyl server. You can monitor the bot's logs and activity through the Pterodactyl panel.

## Support

If you encounter any issues or have questions, please reach out to the support team or join the official Discord server for assistance.

