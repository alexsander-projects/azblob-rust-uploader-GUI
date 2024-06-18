# Rust-azure-storage-uploader-Druid

## Blazing fast Azure Storage Blob uploader for Rust with GUI

![](resources/appUI.png)

- You can upload files to Azure Storage Blob with this app.
- You can upload multiple files at once.

## How to use

The intention of this app is to upload files to Azure Storage Account. This files being inside a folder in the local machine.
The app then creates a folder in the container and uploads the files to that folder.

- You need to have Azure Storage Account and get the Access key.
- You need to create a container in Azure Storage Account.
- You need to provide the container name and access key in the app.
- Provide the file path as well. Eg: `C:\Users\user\files\`
- Provide the name of the folder to be created in the container.
- You can upload files by clicking the "Upload" button.

## How it works

- The app uses the `azure-storage-blob` crate to upload files to Azure Storage Blob.
- The app uses the `druid` crate to create the GUI.
- The app uses the `tokio` crate to run the async functions.

The app's performance is very good. It can upload multiple files at once while using minimal cpu.

Due to the logic of the upload, it may use more memory when uploading large files.

## How to run

Simply run the `.exe` file in the `target\release` folder. The app is already compiled for Windows.