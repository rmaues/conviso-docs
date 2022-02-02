---
id: azure-ad
title: Azure Active Directory
sidebar_label: Azure AD
---

## Introduction

The AD (Active Directory) integration aims to facilitate access to the Conviso Platform and simplify the management of enterprise customer users.

Within Azure's marketplace, you can install Conviso's proprietary application to configure authentication on the platform through SSO.

## Installing the Conviso SSO App

1. Access the [Azure Portal](https://portal.azure.com/) with your admin account:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img1.png)

</div>

2. In the left menu, look for **Azure Active Directory** service, then click at the **Enterprise Applications** menu option:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img2.png)

</div>

3. Select **All Applications** and then click at **+ New Application**:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img3.png)

</div>

4. The **Browse Azure AD Gallery** window will be shown: 

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img4.png)

</div>

5. At the search box, type **AppSec Flow SSO** to search for the app:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img5.png)

</div>

6. Select **AppSec Flow SSO** and install the app by clicking at the **Create** button at the right panel. Wait until its installation is finished:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img6.png)

</div>

7. Click at the recent installed application to open its configuration: 

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img7.png)

</div>

8. Click at the **Single Sign-On** menu on the left:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img8.png)

</div>

9. Copy the required information and paste at the proper form fields at Conviso Platform:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img9.png)

</div>

:::note
After downloading the certificate from Azure, open it in a text editor to copy its contents or use the command ```cat <your_certificate>``` at your terminal to be able to copy its contents.
:::

10. At the **Allowed Domains** field, insert the domain name and all domain aliases used by your organization to log in. After filling the form, click at **Save** button to store your SSO configuration:

<div style={{textAlign: 'center'}}>

![img](../../static/img/azure-ad-img10.png)

</div>

After saving the data and getting a success message, you can test by logging in again using an email from the domain defined in the integration, using the **SSO Access** option in the Conviso Platform login form.

[More information](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/appsec-flow-sso-tutorial)