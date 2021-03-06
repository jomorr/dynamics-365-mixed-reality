---
title: Dynamics 365 Field Service integration with Remote Assist mobile
author: xonatia
description: How Dynamics 365 Field Service integration works with Remote Assist mobile
ms.author: xolee
ms.date: 04/01/2020
ms.service: crm-online
ms.topic: article
ms.reviewer: krbjoran
---
# Use Dynamics 365 Field Service with Remote Assist mobile 

By pairing the Dynamics 365 Remote Assist mobile application with Dynamics 365 Field Service, field service technicians can: 

1. Use Field Service mobile to launch the Remote Assist mobile app and make calls to remote experts on their Android devices.

2. Automatically post **call logs**, such as time, date, call duration, the collaborator's name, and the URLs of the **files shared** in the Remote Assist text chat into their Field Service work order at the end of a Remote Assist mobile call.

Organizations with field service needs can seamlessly capture relevant contextual information from their technicians in the field!

## Prerequisites 
- In order to follow along with this guide, you should have completed the setup instructions for Field Service and Remote Assist integration. Learn how to set up the Dynamics 365 Field Service with Remote Assist mobile [here](../troubleshoot-field-service.md). 

## How it works

Now that we have it enabled, let's see how integration with Field Service works for Remote Assist mobile.

1. At the end of a Remote Assist mobile call, you are prompted to post your call log, if no files are shared, to your Field Service work order. Select **Post**.

![Screenshot of Remote Assist on a mobile device showing the end of a call, with the option to post the call log to a work order.](./media/postfs_2.png "Call log")

2. If files are shared during your Remote Assist call, you will see a list with your call log and files that you can post to your Field Service work order. Select **Post All**.
> [!Tip] 
> If you want to post the Remote Assist call recording to your Field Service work order, you can copy and paste the Microsoft Stream URL that will be in your Microsoft Teams chat into your work order. Remember to adjust the Microsoft Stream permissions to allow access to others. 

![Screenshot of Remote Assist on a mobile device showing the list of items in the call log after the call has ended.](./media/postfs_1.png) 

3. If you have **active bookings** assigned to you through Field Service, you'll see them listed. Select your booking and select **Post**.

![Screenshot of Remote Assist mobile showing available bookings pulled in from Field Service.](./media/post_1.png "Select Booking")

4. If you have no bookings assigned to your account, you can **Refresh** your screen or **Discard** your post.

![Screenshot of Remote Assist mobile showing the option to refresh Dynamics 365.](./media/post_3.png "No Bookings")

5.	If you still don't see the booking you're looking for, it might be because you have access to multiple instances (organizations). You can select the **Ellipses** icon to return to your instance, and then select another **Instance**. Then continue from **Step 3**.

![Screenshot of Remote Assist mobile showing the Select an Instance screen](./media/post_2.png "Select Instance")


6. You will return to your contact list and you will be notified when your call log and files have successfully been posted to your Field Service work order and then you can sign in to your work order.

![Screenshot of Remote Assist mobile on the contacts list, showing a notification that says items have been posted to a work order.](./media/postfs_3.png "End of call notification")

7. You can go to the Field Service work order and view the call log and files that have been posted from Remote Assist mobile. Then you can copy and paste the files URL in a new tab to view the files.  
> [!Note] 
> If someone viewing your Field Service work order, such as an admin or dispatcher, wants to view the files, they must request access to your files on OneDrive. 
