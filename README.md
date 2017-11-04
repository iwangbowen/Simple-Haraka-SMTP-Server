# Simple-Haraka-SMTP-Server
Create simple Haraka SMTP server for local development

## Step 1
Install Python 2.7.14 on windows whether or not you have Python 3.x installed
because node-gyp relies on Python 2.x. Refer to [this page](https://www.npmjs.com/package/node-gyp)
for more information. 
  
  $ npm config set python /path/to/executable/python2.7
## Step 2
Refer to [this link](https://github.com/nodejs/node-gyp/issues/307) when you encounter msbuild error msb3428
after running npm install -g Haraka.
### as admin
  npm install --global --production windows-build-tools

## Step 3
Install Windows Software Development Kit (SDK) for Windows 8.1. [Link](https://developer.microsoft.com/en-us/windows/downloads/windows-8-1-sdk).

## Step 4
Now you can run npm install -g Haraka to install Haraka on your computer successfully.

