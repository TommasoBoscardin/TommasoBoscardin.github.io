---
title: "RFI Feed"
description: "A symple Android app that provides notifications about RFI's news, notices, press releases and infomobility."
publishedAt: 2025-06-16
category: "Android"
---

*Kotlin*

The Android app provides notifications related to RSS feeds made available by RFI. A background worker performs a fetch every 15 minutes to download new data; this fetch can be performed manually. Specifically, users can decide whether to receive the latest news, press releases, mobility information, and alerts. They can also filter feeds by region to receive only relevant updates. A summary of all received feeds is available when the app opens. Clicking on a specific feed brings up a screen with more details and a link to the full story. In the settings page, users can choose to delete the local database and receive a maximum of one notification at a time.

To ensure maximum user customization, the app uses five notification channels. The notification containing a new feed is expandable; clicking it takes you to a screen with all the details and features two buttons: one to open the news item in the browser and the second to open the notification channel settings.

In addition to feed notifications, the app can send a status notification that disappears after 15 minutes and, when clicked, opens the app. Specifically, when a manual data fetch is performed and no new feeds are found, the app notifies the user; when the local database is reset, the app alerts the user; and finally, if the background worker fails to fetch data, it sends a notification.

Project developed for Embedded systems programming course. Full code here.