#!/bin/bash
wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
cd /home/anton/Загрузки/
sudo dpkg -i jenkins_2.303.2_all.deb
sudo apt update
sudo apt install jenkins
