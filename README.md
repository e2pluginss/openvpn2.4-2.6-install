# OpenVPN 2.4 - 2.6 Installer

Welcome to the OpenVPN 2.4 - 2.6 Installer! This script simplifies the process of setting up an OpenVPN server on various Linux distributions, supporting versions from 2.4 to 2.6. It's tailored to be user-friendly, ensuring a smooth installation experience.

## Features

- 🚀 **Easy to Use**: Run a single command, and the script takes care of the rest.
- 🔄 **Supports Multiple Versions**: Compatible with OpenVPN versions 2.4 to 2.6.
- 🖥️ **Wide Distribution Support**: Works on Debian, Ubuntu, Fedora, CentOS, Amazon Linux, Oracle Linux, and Arch Linux.
- 🔒 **Secure Defaults**: Set up with security best practices in mind.
- 📝 **Customizable**: Easily tweak settings to suit your needs.

## Getting Started

### Prerequisites

- A Linux server with one of the supported distributions.
- `root` access or an account with `sudo` privileges.
- An active internet connection.

### Installation

Run the following command in your terminal to start the installation:

```bash

wget https://raw.githubusercontent.com/e2pluginss/openvpn2.4-2.6-install/main/openvpn-install-new.sh && chmod 0777 openvpn-install-new.sh &&  bash openvpn-install-new.sh

```
### Openvpn GUI client

    https://openvpn.net/community-downloads/
    
    https://swupdate.openvpn.org/community/releases/OpenVPN-2.6.8-I001-amd64.msi

### The script will guide you through the process with simple prompts.
### How it Works

    Download and Execute: The script is downloaded and given execute permissions.
    Interactive Setup: The script runs interactively, asking you a series of questions to configure your OpenVPN server.
    Automatic Configuration: Based on your responses, the script automatically sets up OpenVPN on your server.
    Completion: Once the script completes, your OpenVPN server will be up and running.

### Customization

If you need to customize your OpenVPN setup, you can modify the script or answer the interactive prompts accordingly.
Support

Found a bug? Have a suggestion? Please file an issue on our GitHub repository.
License

### This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Thanks to the contributors of the OpenVPN project.
    Special thanks to the open-source community for continuous support and feedback.

