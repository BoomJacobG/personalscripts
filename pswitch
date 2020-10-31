#!/bin/bash

sudo mv /etc/pulse/daemon2.conf /etc/pulse/daemonswitch.conf
sudo mv /etc/pulse/daemon.conf /etc/pulse/daemon2.conf
sudo mv /etc/pulse/daemonswitch.conf /etc/pulse/daemon.conf
pulseaudio -k 
sudo cat /etc/pulse/daemon.conf
