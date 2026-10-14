<p align="center">
  <img src="https://img.shields.io/badge/Developer-EH%20MUNNA-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Termux-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge">
</p>

##  Google Antigravity CLI Installation Guide

**Install Antigravity CLI on Termux | EH MUNNA**

---

##  About

This guide explains how to install and run Google Antigravity CLI
in Termux on Android.

##  Requirements

- Android phone
- Termux
- Internet connection
- Personal Google account eligible to use Antigravity

##  Update Termux

```bash
pkg update && pkg upgrade -y
```
## Install Required Packages
```
pkg install curl git nano -y
```
## Install Antigravity CLI
```
curl -fsSL https://antigravity.google/cli/install.sh | bash
```
## Configure PATH
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
## Check Installation
```
agy --version
```
## Start Antigravity
```
agy
```
## Login
1.Select Google OAuth.
2.Press Enter.
3.Open the authentication link in your 4.browser.
5.Sign in with your Google account.
6.Complete any required verification.
## Eligibility Error
If you see:
Your current account is not eligible for Antigravity
Try the following:
Verify your Google account in the browser.
Check whether your account is eligible for Antigravity.
Try another eligible personal Google account if necessary.
Successful installation does not guarantee account eligibility.
