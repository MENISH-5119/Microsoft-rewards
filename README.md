PYTHON BING REWARDS
Automate Microsoft Bing Rewards searches and earn gift cards faster.

What it does

Automates daily Bing searches with Selenium

Works with Microsoft Rewards + Google account

Potentially earn ₹1500 – ₹2000 Amazon balance every 3 months

Requirements

Python 3.10+

Microsoft Edge browser

Microsoft Rewards account (fresh, not banned😋)

Google account

Installation
Install via pip

Run these in Command Prompt:

pip install selenium


Optional but recommended:

pip install webdriver-manager


This auto-downloads the correct Edge driver when Selenium runs (no manual updates needed).

Manual Driver Setup (if not using webdriver-manager)

Check your Edge browser version:

Open Edge → ... menu → Help & Feedback → About Microsoft Edge

Example: Version 139.0.xxxx.x

Download matching Edge WebDriver from Microsoft:
Download Edge WebDriver

Extract msedgedriver.exe and place it in:

C:\Users\Admin\python code\repos\


(or any folder, but update your script’s DRIVER_PATH accordingly)

Dependencies

No extra installs needed:

time, random, threading → built into Python

winsound → built into Python (Windows only)

Quick Start

At minimum:

pip install selenium


Then either:

Use webdriver-manager (easy, auto-updates driver), OR

Manually download and place msedgedriver.exe

Support

If this project helped you, consider supporting via GitHub Sponsors.
