# a short while

Source code for a sound stretching installation.

This program listens for ambient sounds and chooses some to capture, variably slow down, and play back. It is very configurable so it can easily be "tuned" to fit different environments and noise requirements.

In the field, this is installed on a Raspberry Pi 4 connected to a microphone and speaker.

## Installation

1. [Install a rust toolchain](https://rustup.rs/)
2. Download or clone this repository
3. From within it, run `cargo run -- -h` to build and print the help menu.

## Scripts

Individual installation setup needs will vary, but the particular scripts used in the initial installation at CAVE are kept in `pi_scripts`. They help set up the Pi to run the installation with systemd so it automatically restarts if it crashes. A cron job is used to automatically turn off the program during off-hours.

## Credits

This installation is a collaboration between [Andrew Yoon](https://andrewyoon.art) and [Jonah Udall](https://www.jonahudall.com/). It was initially presented and installed by the [LEIMAY ensemble](http://beta.leimay.org) outside their Williamsburg studio in 2021 and 2022.
