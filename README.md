# Prerequisite: 1. import boto3 2. have aws configured 3. have .pem file

## CreateUser.py & changePassword.py
When a user is there, you cannot create it. So if you are the owner, you can run changePassword.py to change the passoword. It will ask your current password.

## UploadFile.py
It will allow you to upload your file to s3 storage in amazon. But you need to create a account for that.

## ListFile.py
It will list all of your file from s3 storage for you

## GetFile.py
You can download the file from s3 storage. But you need to specify the path for it. If there is a duplicated name in the path that you want it downloaded
It will change the localfile's name to avoid naming conflict.

## Delete.py
You can delete the file in your s3 storage by specifing the file's name you wanna delete.
