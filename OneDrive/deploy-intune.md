---
ms.date: 03/05/2024
title: "Deploy OneDrive apps using Intune"
ms.reviewer: 
ms.author: mactra
author: MachelleTranMSFT
manager: jtremper
audience: Admin
f1.keywords:
- NOCSH
ms.topic: article
ms.service: one-drive
ms.localizationpriority: medium
ms.collection: 
- Strat_OD_admin
- M365-collaboration
ms.custom:
- seo-marvel-apr2020
- onedrive-toc
search.appverid:
- MET150
- ODB160
- MOE150
- MED150
- MBS150
- ODB150
ms.assetid: 3f3a511c-30c6-404a-98bf-76f95c519668
description: "In this article, you'll learn how you can use Intune to deploy the OneDrive mobile app to iOS and Android devices and the OneDrive sync app to Windows 10."
---

# Deploy OneDrive apps by using Intune

If you're a global admin or assigned [a role in Intune](/mem/intune/fundamentals/role-based-access-control) that gives you the necessary permissions, you can use Intune to deploy OneDrive apps. Before you begin deploying, make sure you review the planning information and deployment options in the [Plan file sync for SharePoint and OneDrive in Microsoft 365](plan-file-sync.md).

## Deploy the OneDrive sync app to Windows devices

OneDrive is preinstalled on Windows 10 and later. You can choose to switch to [per-machine installation](per-machine-installation.md).

For info about configuring sync app settings using Intune, see [Configure settings with Intune](configure-sync-intune.md).

## Deploy the OneDrive app to iOS devices

To deploy apps in Intune, you use the [Microsoft Intune admin center](https://intune.microsoft.com/?ref=AdminCenter#blade/Microsoft_Intune_DeviceSettings/AppsMenu/allApps). 

There are two options for deploying the OneDrive app on iOS:
- **Apple VPP.** Using this option and deploying with device licensing, the app is installed without user interaction. For more information, see [How to manage iOS and macOS apps purchased through Apple Business Manager with Microsoft Intune](/mem/intune/apps/vpp-apps-ios).
- **iOS Store app.** Using this option doesn't require any connection to Apple Business Manager, however users will be prompted to enter their Apple ID password to install the app. For more information, see [Add iOS store apps to Microsoft Intune](/mem/intune/apps/store-apps-ios).

## Deploy the OneDrive app to Android devices

- For the steps to deploy apps to Android devices, see [Add Android store apps to Microsoft Intune](/mem/intune/apps/store-apps-android). Use **<https://play.google.com/store/apps/details?id=com.microsoft.skydrive>** as the Appstore URL. For info about assigning apps to groups, see [Assign apps to groups with Microsoft Intune](/mem/intune/apps/apps-deploy).
](https://github.com/scottbreenmsft/OfficeDocs-SharePoint/blob/live/OneDrive/deploy-intune.md)
