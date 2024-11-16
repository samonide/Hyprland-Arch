# Hyprland-Arch

This repository contains configuration and setup files for running **Hyprland** on **Arch Linux**. Hyprland is a dynamic tiling Wayland compositor that aims to be fast and customizable. This repository includes instructions, configurations, and customizations for installing and configuring Hyprland on an Arch Linux system.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hyprland is a modern, dynamic Wayland compositor that provides a high level of customization and performance. It is designed to be modular and works seamlessly with the latest Wayland technologies. This repository aims to provide an easy way to install and configure Hyprland on an Arch Linux machine.

## Installation

Follow these steps to install and set up Hyprland on your Arch Linux system:

### 1. Install Necessary Packages

You will need to install several packages to get Hyprland working on Arch Linux. The following command installs the necessary dependencies:

```bash
sudo pacman -S hyprland swaybg swaylock waybar xorg-xwayland
```
### 2. Install Additional Dependencies

Install any additional tools and utilities you may need for a better experience:

```bash
sudo pacman -S wofi dunst playerctl alacritty
```
### 3. Set Up Hyprland Configuration

Configuration files for Hyprland are included in this repository. To set up the configuration, copy the files to the appropriate directories on your system:

```bash
cp config/* ~/.config/hyprland/
```

### Configuration

You may modify these configuration files to suit your needs. For example, you can adjust the keybindings, appearance, and behavior of your compositor.

The configuration files in this repository allow you to customize the behavior and appearance of Hyprland. The following are some of the key files included:

- **`hyprland.conf`**: Main configuration file for Hyprland settings (e.g., output configuration, keybindings).
- **`waybar/config`**: Configuration for the **Waybar** status bar used with Hyprland.
- **`swaylock.conf`**: Configuration for the lock screen, if you use **Swaylock** as the lock screen for Wayland.

Each configuration file is documented, and you are encouraged to modify them as needed.

### Usage

Once installed and configured, you can start Hyprland by running the following command:

```bash
hyprland
```

To log in to Hyprland as your default session, ensure your display manager is configured to launch Hyprland.

### Contributing

Contributions are welcome! If you find any bugs or have improvements to suggest, please open an issue or submit a pull request. To contribute:

1. Fork this repository.
2. Clone your fork to your local machine.
3. Make your changes in a separate branch.
4. Test your changes.
5. Open a pull request with a detailed description of the changes.

Please ensure that your code adheres to the existing style and passes all tests before submitting a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
