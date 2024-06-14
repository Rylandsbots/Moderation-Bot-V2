# Moderation Bot V2 - Windows Installation

This guide will walk you through the installation process of the Moderation Bot V2 on a Windows computer.

## Prerequisites

- Node.js (v16 or higher) installed on your system
- Git (optional, if cloning the repository)

## Installation

1. **Clone the Repository or Download the Source Code**
   - If you have Git installed, you can clone the repository using: `git clone <repository_url>`
   - Alternatively, you can download the source code as a ZIP file from the repository

2. **Install Dependencies**
   - Open a terminal or command prompt
   - Navigate to the project directory
   - Run the following command to install the required dependencies:
     ```
     npm install
     ```

3. **Set up Configuration**
   - In the project directory, locate the `config.json` file
   - Open the file in a text editor
   - Replace the placeholders with your own values, such as the bot token, client ID, server ID, and MySQL database credentials
   - Save the configuration file

4. **Set up MySQL Database**
   - Install MySQL on your system if you haven't already
   - Create a new database for the bot
   - Update the MySQL database credentials in the `config.json` file

5. **Run the Bot**
   - In the terminal or command prompt, navigate to the project directory
   - Run the following command to start the bot:
     ```
     node src/index.js
     ```

## Configuration

The `config.json` file includes the following sections:

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

After following the installation steps, the bot should be up and running on your Windows computer. You can monitor the bot's activity through the terminal or command prompt.

## Support

If you encounter any issues or have questions, please reach out to the support team or join the official Discord server for assistance.

