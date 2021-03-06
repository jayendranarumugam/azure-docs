---
title: Migrate accounts from Cloud Partner Portal to Microsoft commercial marketplace
description: Learn how to migrate your account from Cloud Partner Portal to Partner Center in Microsoft commercial marketplace for Azure
ms.service: marketplace 
ms.subservice: partnercenter-marketplace-publisher
ms.topic: conceptual
author: parthpandyaMSFT
ms.author: parthp
ms.date: 09/23/2019
---

# How to migrate your account from Cloud Partner Portal to Partner Center

If you have an existing Cloud Partner Portal (CPP) account, your account settings need to be migrated to Partner Center.

## Account migration process

If you're a user with the Owner role in CPP for a given account, a yellow banner is shown on your Publisher Profile page. You may belong to one of the following two cases:

- Your account has already been migrated, and you're ready to manage your Account Settings in Partner Center.
- Your account has not been migrated to Partner Center and you need to take further action.

### Your account has been migrated to Partner Center

You now manage your account in Partner Center. Changes such as user addition/deletion will be synced back to CPP.

### You have not yet migrated your account to Partner Center

Click on the banner to start your account migration process. You're expected to enter the following items:

1. Work email address: <br> <br> In most cases, sign in with the email address that you use to sign into CPP. In certain cases, a different email address must be used:

    * Microsoft account: If the CPP account is a Microsoft account, enter a valid work email associated with the tenant for whom the Microsoft Partner Network (MPN) ID is registered. For more information, see [Sign up for Microsoft Partner Network Program](#sign-up-for-microsoft-partner-network-program).

    * Tenant mismatch: If your work email address does not belong to the tenant that's associated with the Microsoft Partner Network ID present on your CPP account, then you'll see an error. To move past this error, enter an email address associated with the tenant. An error message will provide the name of the tenant.

2. Sign up for Microsoft Partner Network program

    If your CPP account doesn't have a Microsoft Partner Network ID or has one that's invalid, you'll need to sign up for the Microsoft Partner Network program as part of the activation process.

## Publishers moving from CPP

If your account was migrated from the CPP, you don't need to create a new Partner Center account. You should have received a customized link to your new Partner Center account in email and in a banner notification after logging in to your existing CPP account.

Once you've enabled your new Partner Center account by visiting this customized link, you can return to your account by visiting the [commercial marketplace dashboard](https://partner.microsoft.com/dashboard/commercial-marketplace/overview) in Partner Center.

The publishing agreement and company profile information will be migrated to your new Partner Center account, along with any previously set up account payout profile information, user accounts and permissions, and active offers associated with your CPP account.

After your account information is moved from CPP to Partner Center, you'll no longer use CPP to make account updates, or manage users, permissions, and billing. For a limited time, any account updates you make in Partner Center will automatically be updated in your read-only CPP account until the CPP portal is eventually deprecated.

## Sign up for Microsoft Partner Network program

Companies that want to partner with Microsoft must join the Microsoft Partner Network (MPN) and get an MPN ID. If you're already a member of the Microsoft Partner Network and have an MPN ID, keep the information handy as you'll need it during the account activation process.  

If you're not a member of the Microsoft Partner Network, you can [join here](https://signup.microsoft.com/signup?sku=StoreForBusinessIW&origin=partnerdashboard&culture=en-us&ru=https://partner.microsoft.com/dashboard/account/v3/xpu/onboard?ru=/dashboard/account/v3/enrollment/companyprofile/basicpartnernetwork/new) to get an MPN ID. Make a note of your MPN ID as you'll need to enter it during the account activation process.

To learn more about the Microsoft Partner Network, see [Join the Microsoft Partner Network](https://partner.microsoft.com/membership) on the partner website. To learn more about ISV benefits in the Microsoft Partner Network, see the [ISV Resource Hub](https://partner.microsoft.com/isv-resource-hub).  

## Move Dynamics 365 and PowerApps offers to Partner Center

To streamline account and offer management for Dynamics 365 Customer Engagement, PowerApps, and Dynamics 365 Operations, offers have been moved to [Partner Center](https://partner.microsoft.com/). The move ensures the same content is available to both public and seller catalogs.

For specific information on what needs to be done by **October 15, 2019** for your Dynamics 365 Customer Engagement, PowerApps, and Dynamics 365 Operations offers, follow the instructions below.

> [!NOTE]
> This does not apply to Dynamics 365 Business Central offers.  

1. If your MPN membership account was originally created in Partner Membership Center (PMC), sign in to [Partner Center](https://partner.microsoft.com/pcv/accountsettings/connectedpartnerprofile) to confirm that your account has been migrated. If you see a profile screen with your MPN ID, you're ready to continue. If not, you need to start your account migration by following the prompts in the [Partner Membership Center](https://partners.microsoft.com/partnerprogram/Welcome.aspx). If you need help, visit [support](https://partner.microsoft.com/support?issueid=100-0077).
2. Go to the [Commercial Marketplace overview page in Partner Center](https://partner.microsoft.com/dashboard/commercial-marketplace/overview). If you see "Commercial Marketplace" in the left navigation pane, you're enrolled and should continue to the next step. If not, [enroll in the commercial marketplace](https://partner.microsoft.com/dashboard/account/v3/enrollment/introduction/partnership) now.
3. Confirm your offers are in AppSource by [searching for your offers](https://appsource.microsoft.com/). If your offers are already in AppSource, continue to the next step. For any offer not in AppSource, see [Plan a Dynamics 365 Customer Engagement offer](dynamics-365-customer-engage-offer-setup.md) or a [Create a Dynamics 365 Operations offer](.\partner-center-portal\create-new-operations-offer.md).
4. On Partner Center's [Agreements page](https://partner.microsoft.com/dashboard/account/agreements), make sure you've reviewed and accepted the **Business Applications ISV Addendum**.
5. In Partner Center's [Account settings](https://partner.microsoft.com/dashboard/account/v3/accountsettings/billingprofile), make sure your billing information is complete.
6. Submit each new and existing offer for certification and publication, even if your offers were previously certified.
    * Complete the information screens, including providing your app for certification, as well as marketing information. Select **Submit** (top-right corner of the screen) by **October 15, 2019**. These steps must be completed to avoid impacting availability of the offer.
    * If eligible, you may request to participate in the premium tier during this process.
    * Certification or recertification requires that your app supports the latest version of our Business Applications Platform.
    * Once your app has been approved, you'll receive an email to return to the offer and select "go live" to enable the offer to go live on Microsoft AppSource.

## Additional resources

Get help from experts and peers in forums and discover blogs, webinars, videos, events, and more at [Microsoft Dynamics CRM](https://community.dynamics.com/crm?wa=wsignin1.0).

If you need help publishing, certifying, or managing your marketplace offers, [submit a support ticket](https://aka.ms/MarketplacePublisherSupport).

## Next step

- [Manage your commercial marketplace account in Partner Center](./manage-account.md)
