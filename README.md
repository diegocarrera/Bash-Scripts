Bash-Scripts
============

Some useful shell scripts.

<h3>notify-highload.sh </h3>

This script generates a notifcation whenever the CPU load increases beyond a specified limit. There are many customization options available via command line parameters.
- Use `-a` for audio notifications
- Use `-g` for desktop notifications
- Use `-v` for terminal notifications
- Set frequency of check using `-p <seconds>`
- Set the limit for high CPU usage using `-l <number>`. This could be any number greater than 0. The scale is a percentage scale, so ideally it should be between 90-100.
- Choose which load average to use with the `-t <minutes>` option. This can be either 1,5 or 15.
- Set gap between notifications using `-n <seconds>`
- Add initial delay to load checking using `-b <seconds>`

To use this script:
- Create a file called `notify-highload.sh` and paste the code or simply git clone this repository.
- Give the script execution priveleges using `chmod +x ./notify-highload.sh`
- Run from terminal or add it to your startup applications.
