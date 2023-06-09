---
title: "Making it easier to revert"
description: Blog post about how to roll back virtual machine to maintain a good recovery point while in the Windows Insider Program.
author: scooley
ms.author: scooley
date: 2017-04-20 00:48:56
ms.date: 03/20/2019
categories: hyper-v
---
# Making it easier to revert
Sometimes when things go wrong in my environment, I don't want to have to clean it all up -- I just want to go back in time to when everything was working. But remembering to maintain good recovery points isn't easy. Now we're making it so that you can always roll back your virtual machine to a recent good state if you need to. Starting in the latest Windows Insider build, you can now always revert a virtual machine back to the state it started in. In Virtual Machine Connection, just click the Revert button to undo any changes made inside the virtual machine since it last started. <!--[![Revert virtual machine](https://msdnshared.blob.core.windows.net/media/2017/04/Capture21.png)](https://msdnshared.blob.core.windows.net/media/2017/04/Capture21.png) --> Under the hood, we're using checkpoints; when you start a virtual machine that doesn't have any checkpoints, we create one for you so that you can easily roll back to it if something goes wrong, then we clean it up once the virtual machine shuts down cleanly. New virtual machines will be created with "Use automatic checkpoints" enabled by default, but you will have to enable it yourself to use it for existing VMs. The option is off by default on Windows Server.  This option can be found in Settings -> Checkpoints -> "Use automatic checkpoints" <!--[![Checkpoint settings](https://msdnshared.blob.core.windows.net/media/2017/04/Capture5.png)](https://msdnshared.blob.core.windows.net/media/2017/04/Capture5.png)--> Note: the checkpoint will only be taken automatically when the VM starts if it doesn't have other existing checkpoints. Hopefully this will come in handy next time you need to undo something in your VM. If you are in the Windows Insider Program, please give it a try and let us know what you think. Cheers, Andy
