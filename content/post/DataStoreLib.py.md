+++
date = "2017-03-12T12:36:27-04:00"
description = "DataStoreLib.py is a python library used to access and store data on the DataStore API"
draft = false
keywords = [ "SDK", "Python", "REST", "Big Data Management" ]
tags = [ "SDK", "Python", "Python Package", "REST", "Big Data Management" ]
title = "DataStoreLib.py"
topics = ["DataStoreLib.py"]
type = "post"

+++

## Goal
DataStoreLib.py is a python SDK designed to access the DataStore API.


## Implementation
DataStoreLib.py simplifies the DataStore API into two python functions

    #file: file to be passed to requests
    #mimeType: string mimeType
    #data: dictionary of metadata for the file
    DataStore.uploadFile(file, mimeType, data)
    #returns: True or False

    #conditions: array of conditions to pass to DataStore.
    #   Syntax in the DataStore documentation
    DataStore.getIds(conditions)
    #returns: array of urls to files passing the conditions

## Completed

 - Uploading Files
 - Searching metadata

## Future goals

None yet


[Source Code](https://github.com/cyberpirate/DataStoreLib.py)