# Box64Droid
Personal testing of Older Wine Versions on Box64droid.

## Installation instructions
1. Install [Termux](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk) and [Termux-x11](https://github.com/laytewon/OldWine-Box64Droid/releases/download/stable/app-arm64-v8a-debug.apk).
2. In Termux, run the Box64Droid install command: `curl -o install https://raw.githubusercontent.com/laytewon/OldWine-Box64Droid/main/installers/install.sh && chmod +x install && ./install`

After the installation is completed, run `box64droid --start`. The script will start Termux-X11 and show the start menu.



Credits to original Auther:
Made by a guy from [Lysychansk](https://en.wikipedia.org/wiki/Lysychansk), [Luhansk region](https://en.wikipedia.org/wiki/Luhansk_Oblast) of Ukraine.

News about the original project are published on the [Telegram](https://t.me/box64droidch) channel.

## Thanks to:
- [Herick75](https://github.com/Herick75) - for providing patches that made compiling Mesa Turnip possible
- [Inguna87](https://github.com/inguna87) - for start chroot fix for MIUI and Oxygen
- [Alfhashut](https://github.com/alfhashut) - inspired me to try VirGL again and tried to help me with it
