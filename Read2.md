# Welcome to the (growing) online documentation of Picture Sync

## Quick start
1. Create a share on your Windows machine
2. Grant a local user access to it as read & write
3. Install the app on your phone
4. Setup the app by specifying your window share and your username & password

## What is it
Picture Sync is a relatively simple application which scans the pictures on your phone and enable you to sync them on a Windows share or any other SMB share.

## How to use it
1. Setup your windows share
2. Setup the app
3. Return to the main page (back button)
4. From the main page, simply press the bottom right button to sync

## What is required
- You must provide a Windows share or any other SMB share like from your NAS device.
- You must have a local username & password that your phone uses to connect to your share.
- Your phone must be able to connect to your share, as usually your PC or NAS device is not directly visible on internet,
your phone must be on the same network (for example via WIFI) during the sync operation.

## How do I setup a Windows Share?
1. Create the folder you want to sync your images to 
2. Right click on the file you have created and open proprties 
3. Select the sharing tab and click on share 
4. Give your user Read/Write permissions then click share 
  Now you should now be able to copy images to the folder you have just created 
<!--![share0](https://user-images.githubusercontent.com/32289945/169647099-6d3265f8-402f-47dd-9748-d52b106069d8.jpg)

 ![Share1](https://user-images.githubusercontent.com/32289945/169647102-8d0d48c5-a20c-42c5-957f-a1422965c0a9.jpg)--->

```

## Can I use a Microsoft account?
You should be able to use your Microsoft account via the following syntax as username:
```
MicrosoftAccount\me@domain.com
```
Make sure to keep the ```MicrosoftAccount``` part in your username. If it doesn't work, try to disable the "PIN" login (Settings > Accounts > Sign in options > PIN).

## How can I access my PC on my local LAN?
It usually works better if you provide the IP address of your PC. To know find your IP:
[Find your IP](https://support.microsoft.com/en-us/windows/find-your-ip-address-in-windows-f21a9bbc-c582-55cd-35e0-73431160a1b9)
Your share will then look like something like: ```\\192.168.1.20\yourshare```

## What if I don't want to sync all my old pictures?
In the settings page, press the "Clear" button, and only pictures after that moment will be sync.

## What if I want to re-sync again all?
In the settings page, press the "Reset" button, and all the pictures are marked for sync.

## Does the sync work in background?
Yes the APP is able to sync in background automatically, however you may need to allow it to run in background:
- Set the app as unrestricted for the battery usage
- Allow the app to use data even if the data saving is enabled.

## Can I disable the automatic sync?
Yes! In the APP, go to the settings and disable the auto-sync.

## Can I choose which folder to sync?
Yes! In the APP, go to the settings and choose which folder to sync. The APP shows all the picture's folders found on your device. By having removing the checkbox on one entry you will disable that folder from the sync operation.
