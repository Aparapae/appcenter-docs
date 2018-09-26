---
title: "Side-by-Side Experience"
description: Using HockeyApp and App Center Side-by-Side
author: gaknoll
ms.author: gaknoll
ms.date: 09/26/2018
ms.topic: article
ms.assetid: 79c7beae-c1cd-11e8-a355-529269fb1459
ms.service: vs-appcenter
---

#Side-by-Side Experience

With the side-by-side experience all your HockeyApp apps will be automatically available in App Center. In addition, all your HockeyApp distribution groups will be available in App Center. All releases that have been done through HockeyApp will also be visible in App Center as well.
In the side by side experience, the upload of new releases can be done in either HockeyApp or App Center, either location will be kept in sync in both experiences. Legacy distribution groups will be automatically created in App Center. These legacy groups will by kept in sync with HockeyApp. Any release to a legacy distribution group will be added to HockeyApp and testers will be notified and install unchanged via the HockeyApp experience.

## Getting Started with Side-by-Side

As a HockeyApp customer, your account has automatically been synced and is ready for you in App Center. Therefore, getting started with the side-by-side experience is easy:

1.	[Sign-in](https://appcenter.ms/login?utm_medium=referral_link&utm_source=Hockey%20App) to App Center with your HockeyApp Credentials

![App Center Sign-In](~/migration/hockeyapp/images/appcenter-sign-in.png)

2.	Once logged in, you'll see a list of all of your existing HockeyApp apps. HockeyApp side-by-side apps are marked with a blue HockeyApp icon. 

![HockeyApp apps in App Center](~/migration/hockeyapp/images/hockeyapp-apps-in-appcenter.png)

## Getting the Most from the Side-by-Side Experience

* Extend your test suite using our brand new cloud based [continuous integration](~/build/index.md) and [automated UI testing](~/test-cloud/index.md) services without affecting your HockeyApp workflow.

* App Center's **Distribute** service works alongside HockeyApp. Upload and distribute your new releases using App Center, all while automatically syncing with your HockeyApp account. [More details here](~/migration/hockeyapp/distribution.md)

* App Center's **Crashes** and **Analytics** services will automatically stream data collected from your existing HockeyApp SDK directly into App Center. Note that the App Center Crash service is currently in preview for HockeyApp apps. You can join the preview on the Crash page in App Center to begin collecting crash data. 

## Side-by-Side Limitations

During this period, all app management (Collaborators, notifications, renaming app, deleting app, etc) will remain in HockeyApp. To easily access the HockeyApp version, click the link in the upper, right-hand corner of the 'Getting Started' page in your app.