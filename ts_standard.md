---



copyright:

  years: 2017
lastupdated: "2017-05-30"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Troubleshooting Standard account 
{: #stdaccountts}

Before contacting {{site.data.keyword.Bluemix_notm}} support, check to see if the problem you're experiencing in your Standard account is explained in this troubleshooting section.
{:shortdesc}

## Unable to access a different {{site.data.keyword.Bluemix_notm}} region
{: #nosecondreg}

### What's happening
You try to access a {{site.data.keyword.Bluemix_notm}} region that is different to the region where your account was created but the Upgrade Your Account window is displayed. 

### Why it's happening
A Standard account supports development in one region only and you select the {{site.data.keyword.Bluemix_notm}} Public region in which you want to work when the account is first set up. 

### How to fix it
If you want to access more than one geographical region, you must upgrade to a billable account. For more information, see [Signing up for a billable account](/docs/pricing/index.html#pay-accounts).  

## Unable to create new organization
{: #nosecondorg}

### What's happening
You try to create a second organization in your Standard account but the Upgrade Your Account window is displayed. 

### Why it's happening
A Standard account supports development in one organization only, which is created when your account is first set up. 

### How to fix it
If you want to use more than one organization, you must upgrade to a billable account. For more information, see [Signing up for a billable account](/docs/pricing/index.html#pay-accounts).    

## Unable to create new Lite plan instance
{: #nosecondlite}

### What's happening
You try to create a second instance for a particular service Lite plan but the instance is not created. The following error message is displayed:

`Unable to provision new Lite instance`

### Why it's happening
You can provision one instance only for a Lite plan. 

### How to fix it
To create more than one instance for a Lite plan, you must upgrade to a billable account to use a different service plan. If you do not want to upgrade from a Standard account, you can delete the exisiting Lite plan instance from the Services dashboard and then create a new instance. For more information, see [Signing up for a billable account](/docs/pricing/index.html#pay-accounts).   

## Exceeded the runtime memory allowance
{: #noruntimemem}

### What's happening
You exceed the runtime memory allowance of 256 MB and you are prompted to upgrade to a billable account.

### Why it's happening
In a Standard account your apps can use up to 256 MB only of runtime memory. 

### How to fix it
To obtain more runtime memory, you can upgrade to a billable account. For more information, see [Signing up for a billable account](/docs/pricing/index.html#pay-accounts). 

If you do not want to upgrade from a Standard account, you can delete another instance to free up some runtime memory. 
