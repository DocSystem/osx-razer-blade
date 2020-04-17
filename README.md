# osx-razer-blade

This project was originally created by [kprinssuu](https://github.com/kprinssu/osx-razer-blade). I forked it because the drivers weren't up to date and it didn't work with my Razer Blade 2019 Base Model. If you want the command line tool, here it is: [osx-razer-led](https://github.com/DocSystem/osx-razer-led).

Userland console application to control lights on Razer Blade that are running a Hackintosh (macOS on a non-Apple device).

The tool is currently a proof of concept and is intended for use by developers. The Razer driver logic was ported from the Linux project, https://github.com/terrycain/razer-drivers/.

Xcode is needed to build and run this project.

Usage:
1. Clone the repo
2. Edit the `razer_attr_write_mode_breath` line (in main.m) with your own effect (see header file in razer_knd.h).
3. Build and run the project.

This project unless otherwise stated in the file is licensed under the GPLv2 license.
