---
title: Difference between Full, Limited, and Self Service User Types
description: This article provides the answer for the question about what is the difference between Full, Limited, and Self Service User Types in User Setup in Microsoft Dynamics GP.
ms.reviewer: cwaswick
ms.topic: article
ms.date: 03/31/2021
---
# Difference between Full, Limited, and Self Service User Types in User Setup in Microsoft Dynamics GP

This article introduces the difference between Full, Limited, and Self Service User Types in User Setup in Microsoft Dynamics GP.

_Applies to:_ &nbsp; Microsoft Dynamics GP  
_Original KB number:_ &nbsp; 4015051

## Question

In the **User Setup** window, what is the difference between Full, Limited, and Self Service User Types?

To open this window, select **Tools** under **Microsoft Dynamics GP**, point to **Setup**, point to **System**, and select **User**.

## Answer

At a high level, the permissions for each user Type are as follows:

- Self Service - Provides the following abilities:
  - Ability to create requisitions
  - Ability to enter Payroll Timecards and expenses
  - Ability to enter Project timesheets and expenses, benefits self service,  and workflow. (Also known as Enter access)

- Limited- Can do all the Self Service user can do, plus view all inquiry, reports, and Smartlists. (Also known as Enter and Inquire access)

- Full- Has full control in Microsoft Dynamics GP. (Also known as Enter, Inquire, and Edit access)

## More information

The best way to really understand what the users can do is to look at the role-based security inside Microsoft Dynamics GP. For more information, review these blog articles below:

- [What are the SelfServe and Limited Users?](https://community.dynamics.com/gp/b/gpteamblog/archive/2014/12/17/what-are-the-self-serve-and-limited-users)
- [ESS Security roles in Microsoft Dynamics GP 2013/GP2015 - What do they give users access to?](https://community.dynamics.com/gp/b/dynamicsgp/posts/ess-security-roles-in-microsoft-dynamics-gp-2013-and-microsoft-dynamics-gp-2015-what-do-they-give-users-access-to)