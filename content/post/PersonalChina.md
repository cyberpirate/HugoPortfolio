+++
date = "2017-05-12T15:00:10-04:00"
description = "A python script designed to run on the EdgeRouter X that creates and configures an outgoing whitelist firewall."
draft = false
tags = [ "Firewall", "Python", "Linux", "VyOS", "EdgeOS", "EdgeRouter", "sqlite3"]
title = "PersonalChina"
topics = []

+++

## Goal
The goal of this project is to ensure that any software on my system can not phone home without my express approval.

## Implementation
This project configures VyOS firewall rules to create a whitelist that the firewall uses to filter traffic.

## Completed
 - rule configuration
 - command line interface
 - expiring rules

## Future goals
 - web interface
 - blocked request log

[Source Code](https://github.com/cyberpirate/PersonalChina)