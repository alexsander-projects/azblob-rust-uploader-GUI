# Rust blob uploader with GUI for Azure Storage

## Blazing fast Azure Storage Blob uploader for Rust with Druid GUI

![](resources/appUI.png)

### How it works

This is a simple Rust application that allows you to upload files to Azure Storage Blob. It uses the Azure SDK for 
Rust to upload files to Azure Storage Blob. The application is built with Druid, a Rust-native GUI toolkit.

### How to use

1. Pass in your Container name, Folder path, Upload Folder, Storage Account name, and Storage Account key in the respective fields.
2. Click on the "Upload" button to upload the file to Azure Storage Blob.

Container name: The name of the container in Azure Storage Blob where you want to upload the file.
Folder path: The path of the folder where the file is located. For example, if the file is located in the "C:\Users\username\Documents" folder,
then the folder path is "C:\Users\username\Documents".
