I need to install node_exporter latest version with automatically. I decided to turn the installation steps into bash script. 

## Information
- x86_64 based support
- arm64 based support
- Tested on Amazon Linux 2, ubuntu, Debian, CentOS7, CentOS8

## Requirements
- Freshly installed server or doesn't contains a user with name "node-exporter"
- sudo privileges

## Installation
`sh <(curl https://raw.githubusercontent.com/flightlesstux/node_exporter/master/installer.sh)`