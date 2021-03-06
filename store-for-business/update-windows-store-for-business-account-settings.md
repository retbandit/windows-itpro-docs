---
title: Update Microsoft Store for Business and Microsoft Store for Education account settings (Windows 10)
description: The Account information page in Microsoft Store for Business and Microsoft Store for Education shows information about your organization that you can update, including country or region, organization name, default domain, and language preference.
ms.prod: w10
ms.mktglfcycl: manage
ms.sitesec: library
ms.pagetype: store
author: TrudyHa
localizationpriority: high
---

# Update Microsoft Store for Business and Microsoft Store for Education account settings

**Applies to**

-   Windows 10
-   Windows 10 Mobile

The **Payments & billing** page in Microsoft Store for Business allows you to manage organization information, billing information, and payment options. The organization information and payment options are required before you can acquire apps that have a price.

## Organization information
 
We need your business address, email contact, and tax-exemption certificates that apply to your country or locale.
 
### Business address and email contact

Before purchasing apps that have a fee, you need to add or update your organization's business address, and contact email address. 

We use the Business address to calculate sales tax. If your organization's address has already been entered for other commercial purchases through Microsoft Store, or through other online purchases such as Office 365 or Azure subscriptions, then we’ll use the same address in Microsoft Store for Business and Microsoft Store for Education. If we don’t have an address, we’ll ask you to enter it during your first purchase. 

We need an email address in case we need to contact you about your Microsoft Store for Business and Education account. This email account should reach the admin for your organization’s Office 365 or Azure AD tenant that is used with Microsoft Store. 

**To update Organization information**
1. Sign in to the [Store for Business](http://businessstore.microsoft.com) or [Store for Education](https://educationstore.microsoft.com)
2. Click **Manage**, click **Payments & billing**, and then click **Edit**.

## Organization tax information   
Taxes for Microsoft Store for Business purchases are determined by your business address. Businesses in these countries can provide their VAT number or local equivalent:
- Austria
- Belgium
- Bulgaria
- Croatia
- Cyprus
- Czech Republic
- Denmark
- Estonia
- Finland
- France
- Germany
- Greece
- Hungary
- Ireland
- Italy
- Latvia
- Liechtenstein
- Lithuania
- Luxembourg
- Malta
- Netherlands
- Norway
- Poland
- Portugal
- Romania
- Slovakia
- South Africa
- Spain
- Sweden
- Switzerland
- United Kingdom

These countries can provide their VAT number or local equivalent in **Payments & billing**.   

|Market| Tax identifier |
|------|----------------|
| Australia | ABN (optional) |
| Brazil | CNPJ (required) |
| India | CST ID, VAT ID (both are optional) |
| New Zealand | GST Registration number (optional) |
| Taiwan | VAT ID (optional) |

### Tax-exempt status 

If you qualify for tax-exempt status in your market, start a service request to establish tax exempt status for your organization. 

**To start a service request**
1.  Sign in to the [Store for Business](http://businessstore.microsoft.com).
2.	Click **Support**, and then under **Store or account support** click **Start a service request**.

You’ll need this documentation:

|Country or locale | Documentation |
|------------------|----------------|
| United States | Sales Tax Exemption Certificate |
| Canada | Certificate of Exemption (or equivalent letter of authorization) |
| Ireland | 13B/56A Tax Exemption Certificate| 
| International organizations that hold tax exaemption | Certification / letter confirmation from local tax authorities |


### Calculating tax

Sales taxes are calculated against the unit price, and then aggregated. 
 
For example:<br>
(unit price X tax rate) X quantity = total sales tax

-or-

($1.29 X .095) X 100 = $12.25

## Payment options
You can purchase apps from Microsoft Store for Business using your credit card. You can enter your credit card information on Account Information, or when you purchase an app. We currently accept these credit cards: 
1. VISA 
2. MasterCard 
3. Discover 
4. American Express 
5. Japan Commercial Bureau (JCB)

> [!NOTE]
> Not all cards available in all countries. When you add a payment option, Store for Business shows which cards are available in your region.

**To add a new payment option** 

1. Sign in to the [Store for Business](http://businessstore.microsoft.com) or [Store for Education](https://educationstore.microsoft.com). 
2. Click **Manage**, and then click **Payments & billing**. 
3. Under **Payment options**, click **Show my payment options**, and then select the type of credit card that you want to add. 
4. Add information to any required fields, and then click **Next**. 

Once you click Next, the information you provided will be validated with a test authorization transaction and, if validated, the payment option will be added to your list of available payment options. Otherwise, you will be prompted for additional information or notified if there are any problems. 

> [!NOTE]
> When adding credit or debit cards, you may be prompted to enter a CVV. The CVV is only used for verification purposes and is not stored in our systems after validation.  

**To update a payment option** 

1. Sign in to the [Store for Business](http://businessstore.microsoft.com) or [Store for Education](https://educationstore.microsoft.com). 
2. Click **Manage**, and then click **Payments & billng**. 
3. Under **Payment options** > **Show my payment options**, select the payment option that you want to update, and then click **Update**. 
4. Enter any updated information in the appropriate fields, and then click **Next**. 
Once you click **Next**, the information you provided will be validated with a test authorization transaction and, if validated, the payment option will be added to your list of available payment options. Otherwise,you will be prompted for additional information or notified if there are any problems. 
 
> [!NOTE]
> Certain actions, like updating or adding a payment option, require temporary “test authorization” transactions to validate the payment option. These may appear on your statement as $0.00 authorizations or as small pending transactions. These transactions are temporary and should not impact your account unless you make several changes in a short period of time, or have a low balance.

## Offline licensing

Offline licensing is a new licensing option for Windows 10. With offline licenses, organizations can cache apps and their licenses to deploy within their network. ISVs or devs can opt-in their apps for offline licensing when they submit them to the developer center. Only apps that are opted in to offline licensing will show that they are available for offline licensing in Store for Business. This model means organizations can deploy apps when users or devices do not have connectivity to the Store. For more information on the Store for Business licensing model, see [licensing model](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business#licensing-model).

Admins can decide whether or not offline licenses are shown for apps in Microsoft Store. 

**To set offline license visibility**

1. Sign in to the [Store for Business](http://businessstore.microsoft.com) or [Store for Education](https://educationstore.microsoft.com). 
2. Click **Manage**, and then click **Payments & billing**. 
3. Under **Offline licensing**, click **Show offline licensed apps to people shopping in the store** to show availability for both online and offline licenses.

You have the following distribution options for offline-licensed apps:
- Include the app in a provisioning package, and then use it as part of imaging a device.
- Distribute the app through a management tool. 
For more information, see [Distribute apps to your employees from the Store for Business](distribute-apps-with-management-tool.md).