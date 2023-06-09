---
title: Announcing the release of Hyper-V Containers in Windows Server 2016 Technical Preview 4
description: Learn about Hyper-V containers, a new feature in Windows Server 2016 Technical Preview 4.
author: thecloudtaylor
ms.author: taylorb
date:       2015-11-19 08:04:51
ms.date: 11/19/2015
categories: uncategorized
---
# Announcing the release of Hyper-V Containers in Windows Server 2016 Technical Preview 4

Today marks an exciting moment on the journey to bring world class container technologies and options to our customers. With the release of Windows Server 2016 Technical Preview 4, we’re excited to showcase the next major step in our container journey with the first public preview of Hyper-V Containers, as well as significant enhancements to both Windows Server Containers and the Docker engine for Windows.

We heard from you that you want the advantages of containers, including speed, simplified DevOps, and increased flexibility in application development, on Windows Server with support for existing Windows applications and technologies. A few months ago, we released a preview of both Windows Server Containers and, in partnership with the Docker community, a preview of the Docker engine for Windows.  Expanding your choices with containers, today’s release of Hyper-V Containers brings you a new deployment option with increased isolation. Ensuring applications are hosted with the appropriate level of isolation is vital to the security of your infrastructure. Hyper-V Containers isolate applications with the guarantees associated with traditional virtualization, but with the ease, image format and management model of Windows Server Containers, including the support of Docker Engine.  You can make the choice at deployment of whether your application needs the isolation provided by Hyper-V Containers or not, without having to make any changes to the container image or the container configuration.  To learn more, check out Mark Russinovich’s post [Containers: Docker, Windows and Trends](https://azure.microsoft.com/blog/containers-docker-windows-and-trends/), as well as watching the Microsoft Mechanics episode, [Early look at containers in Windows Server, Hyper-V and Azure](https://youtu.be/YoA_MMlGPRc?list=PLXtHYVsvn_b8UbQ8kHbS4tRvEXt9okedN), to learn about Hyper-V container scenarios.  

Since August, we’ve also been hard at work enhancing Windows Server Containers. Your feedback on the Windows container forum has been immensely valuable, and I’m happy to say we’ve addressed many of the issues you reported.  Application compatibility was a key focus, and while we still have some work ahead of us, a number of key applications and application frameworks now work in Windows Server Containers, including ASP.Net 3.5 and 4.6.  You can now use [Nano Server](https://cloudblogs.microsoft.com/windowsserver/2015/04/08/microsoft-announces-nano-server-for-modern-apps-and-cloud/) as both a container host and as a container runtime (the operating system that runs inside the container), providing a lean, efficient installation of Windows Server ideal for born-in-the-cloud applications. We also added shared folder support (also known as volumes in Docker), hostname configuration, and much more. You can find more details on these and other feature improvements, along with updated content and guidance,  on the [Windows Server Containers](/virtualization/windowscontainers/about/) site.

Reading blog posts and watching demos is never quite the same as getting your hands on new technology, playing with it, and building an application with it.  As of today, you can run both Windows Server and Hyper-V Containers by downloading Windows Server 2016 Technical Preview 4 to install on your own systems, and you can experiment with Windows Server Containers by spinning up a Windows Server 2016 Technical Preview 4 virtual machine in Azure straight from the [marketplace](https://azure.microsoft.com/marketplace/). We look forward to your continued [feedback](https://social.msdn.microsoft.com/Forums/en-US/home?forum=windowscontainers)!

 

Taylor Brown  
Lead Program Manager Windows Server and Hyper-V Containers  

