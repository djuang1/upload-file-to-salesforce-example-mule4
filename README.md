# Upload and link files to Salesforce objects using the MuleSoft Salesforce Connector
This is an example project that demonstrates how to upload and link a file to a Salesforce object using MuleSoft and the Anypoint Platform.

<img src="https://raw.githubusercontent.com/djuang1/djuang1.github.io/master/img/upload-file-to-salesforce/upload-file-sfdc.png"/>

## Pre-Requisites
- Anypoint Studio 7.5.0
    - Salesforce Connector 10.1.0
    - File 1.3.2
- Mule EE 4.3.0
- Salesforce Account

## Overview

Querying or upserting data into Salesforce objects is a simple process with MuleSoft and the Salesforce Connector. You can retrieve a Contact record, or update an Account through a single operation generally in Anypoint Studio. But there are some use cases where you need to combine multiple operations to handle a task in Salesforce. One of which, that comes up often, is uploading and attaching a file to an object. 

This project will demonstrate a flow that uploads a file using the Salesforce Connector and links it to a Contact object in a simple Mule flow. The source will be a file picked up by the File Connector but you can swap out that source that results in a file in the payload.
