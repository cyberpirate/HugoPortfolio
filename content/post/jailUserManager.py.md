+++
date = "2017-06-12T15:23:23-04:00"
description = "A small python script to manage permissions on my FreeNAS home server"
draft = false
tags = [ "Python", "Linux Permissions", "FreeNAS", "Linux"]
title = "jailUserManager.py"
topics = []

+++

## Goal
Fix incorrect permissions on mounted files in FreeNAS and add relevant users/groups to any jails that need access to files.

## Implementation
This python script scans the configured folders for incorrect permissions and fixes them. It also scans any jails for missing users/groups and adds them if neccessary.

## Completed
 - Scans for incorrect permissions
 - Scans for missing users in jails

## Future goals

None yet

[Source Code](https://gist.github.com/cyberpirate/a5fd937f07229648e9262fa497ef10bb)