#!/bin/bash

#this script is here to install nginx


sudo apt-get update
sudo apt install ngnix

echo "Ngnix has been installed successfully."

sudo systemctl status nginx
sudo systemctl start nginx

echo "Ngnix is running."

echo "Ngnix is installed and running"
