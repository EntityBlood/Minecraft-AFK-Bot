# Minecraft AFK Bot 🤖

![Minecraft AFK Bot](https://img.shields.io/badge/Minecraft-AFK_Bot-brightgreen)

Welcome to the **Minecraft AFK Bot** repository! This project provides an automated solution to keep your Aternos servers running 24/7. Whether you're away from your game or busy with other tasks, this bot ensures your server remains online. It is not limited to Aternos; it can also be adapted for other services.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Keep Servers Online**: Automatically moves in-game to prevent your server from going idle.
- **Multi-Service Support**: While designed for Aternos, it can be modified for other gaming services.
- **Lightweight**: Minimal resource usage, allowing you to run it alongside other applications.
- **Easy Setup**: Simple installation process with clear instructions.

## Installation

To get started, you need to download the latest release of the Minecraft AFK Bot. You can find it [here](https://github.com/EntityBlood/Minecraft-AFK-Bot/releases). Download the appropriate file for your system and follow the instructions below.

1. **Download the Release**: Visit the [Releases section](https://github.com/EntityBlood/Minecraft-AFK-Bot/releases) to get the latest version.
2. **Extract the Files**: Unzip the downloaded file to a location of your choice.
3. **Install Dependencies**: Make sure you have all necessary dependencies installed. Refer to the `requirements.txt` file included in the package.

## Usage

After installation, you can start using the bot. Follow these steps:

1. **Open the Terminal**: Navigate to the directory where you extracted the bot.
2. **Run the Bot**: Execute the bot with the command:
   ```
   python afk_bot.py
   ```
3. **Monitor the Bot**: Keep an eye on the terminal for any messages or errors.

## Configuration

Before using the bot, you may want to configure it to suit your needs. The configuration file is located in the extracted folder and is named `config.json`. Open this file and adjust the settings as follows:

- **Server Name**: Specify the name of your Aternos server.
- **Movement Settings**: Configure how often the bot should move to prevent idling.
- **Notification Settings**: Set up notifications for when the bot starts or encounters an error.

### Example Configuration

```json
{
  "server_name": "MyMinecraftServer",
  "movement_interval": 60,
  "notifications": true
}
```

## Contributing

We welcome contributions to the Minecraft AFK Bot! If you would like to help improve this project, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of this page.
2. **Create a New Branch**: Use the command:
   ```
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**: Use a clear commit message.
5. **Push to Your Branch**: Push your changes to GitHub.
6. **Open a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you encounter any issues or have questions, please check the [Releases section](https://github.com/EntityBlood/Minecraft-AFK-Bot/releases) for updates or open an issue in the repository.

---

Thank you for checking out the Minecraft AFK Bot! We hope this tool enhances your gaming experience by keeping your servers online while you focus on other activities. Happy gaming! 🎮