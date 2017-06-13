# Go Development Environment

## Description

OS agnostic development environment for Go development. 

## Installation requirements

* Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html)
* Clone this repo

## Commands

Start:

`$ vagrant up`

This does the following:

* Installs Git
* Downloads Go version 1.8.3 and installs it

SSH into the server

`$ vagrant ssh`

Check Go version- This should display the version of go installed.

`$ go version`

cd into src folder and get hacking!

`$ go run main.go`