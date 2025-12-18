# Vagrant CentOS Stream 9 Apache Setup 

## Description
This project provides a Vagrant configuration to quickly spin up a **CentOS Stream 9** virtual machine with **Apache web server**. It automatically deploys a sample **mini finance website** for testing or learning purposes.

---

## Features
- Vagrant VM with **CentOS Stream 9**
- Apache (`httpd`) installed and configured
- Automatically downloads and deploys a demo finance website
- Private and public network configuration
- 1 GB RAM allocated (configurable)
- Simple provisioning using a shell script

---

## Prerequisites
- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) (or another supported provider)
- Internet connection (to download the website template)

---

## Usage

1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>
