+++
author = "Joseph Iacoviello"
date = "2017-06-12T14:36:27-04:00"
description = "DataStore is an api written in PHP using a MySQL database to store and index data for big data solutions"
draft = false
keywords = [ "API", "PHP", "MySQL", "REST", "Big Data Management", "DataStore" ]
tags = [ "API", "PHP", "MySQL", "REST", "Big Data Management" ]
title = "DataStore"
topics = ["DataStore API"]
type = "post"

+++

## Goal
DataStore is designed to store many small files with metadata attached to each file. This metadata could be searched later to download the files that fit the search query.


## Implementation
DataStore is written using php for processing. MySQL is used to store and search the metadata and Apache is used to serve the uploaded files.

## Completed

 - Uploading Files
 - Searching Metadata
 - Downloading Files

## Future goals

 - Auto setup for database tables
 - Auto backup for metadata


[Source Code](https://github.com/cyberpirate/DataStore)