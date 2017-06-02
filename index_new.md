---

copyright:

  years: 2015, 2017
lastupdated: "2017-05-30"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Try {{site.data.keyword.Bluemix_notm}}: Standard account
{: #trystandard}

Standard accounts are available only in the United Kingdom region. Sign up for a free Standard account to build apps and explore services with free Lite plans in {{site.data.keyword.Bluemix}}. Your Standard account doesn't expire and your credit card isn't required.  
{:shortdesc}

When you sign up for a Standard account, you can select which geographical region you want to work in. After you create an org in a region, it can't be changed. 

## What's available? 
{: #whatsavailable}

You might be wondering what the Standard account offers. Check out the following list of key details about the Bluemix Standard account.
  * The account is free -- no credit card required!
  * The account never expires. 
  * You can use one org in one {{site.data.keyword.Bluemix_notm}} region.
  * Free {{site.data.keyword.Bluemix_notm}} support.
  * Cloud Foundry apps can access up to 256 MB of free, instantaneous runtime memory.
  * You can access free Lite plans for select services, with more coming soon.
  * You receive email notifications about your account status.
  * After 10 days of no development activity, your apps go to sleep.
  * After 30 days of no development activity, your service instances with Lite plans are deleted.
  
Although Cloud Foundry apps can access up to a maximum of 256 MB of instantaneous runtime memory, if you exceed your allocated quota, you can stop some of your apps to free up runtime memory. 

## Apps and services with Lite plans

Currently, the following {{site.data.keyword.Bluemix_notm}} apps and services have Lite plans:

<ul>
<li>{{site.data.keyword.mobilepushfull}}</li>
<li>{{site.data.keyword.cloudantfull}}</li>
<li>{{site.data.keyword.conversationfull}}</li>
<li>{{site.data.keyword.iot_full}}</li>
<li>{{site.data.keyword.languagetranslatorfull}}</li>
<li>{{site.data.keyword.personalityinsightsfull}}</li>
<li>{{site.data.keyword.toneanalyzerfull}}</li>
</ul>

We’ll be adding to this list of services, so stay tuned!

Some services are not available in all {{site.data.keyword.Bluemix_notm}} regions. For more information, see [Services by region](/docs/services/services_region.html#services_region).

## Quota limits

When quota limits are reached, your application is stopped or your service is disabled. If the Lite plan specifies that the quota is provided on a monthly basis, the resource usage is reset on the 1st of every month when you can resume working with the service. You receive a notification email When you're approaching or are at the quota limit.

You can provision 1 instance per Lite plan. 

**Note**: These limitations apply to a Standard account only. At any time, you can upgrade to a Pay-As-You-Go or a Subscription account. You pay only for what you use beyond the free allowances. For more information about Pay-As-You-Go and Subscription accounts, see [Billable accounts](/docs/pricing/billable.html).

When you are signed up for a Standard account, you can invite team members to collaborate in your organization and spaces, view your usage, create spaces, update your account profile, and manage your organization. For more 
information, see [Managing your account](/docs/admin/adminpublic.html#account).

## Lite plans
{: #liteplans}
   
Lite plans, which are also available in a Pay-As-You-Go Account, are structured as a free quota. You can work on your projects worry free, without the risk of generating an accidental bill. 
The quota might operate for a specific time period, for example, a month, or on a one-off usage basis. Here are some examples of Lite plan quotas:

<ul>
<li>Maximum number of registered devices.</li>
<li>Maximum number of application bindings.</li>
<li>Encrypted data storage limit, for example, 1 GB.</li>
<li>Provisioned throughput capacity.</li>
</ul> 

In a Standard account, you can use anything in the {{site.data.keyword.Bluemix_notm}} catalog that has a Lite plan. Lite plans are easy to find. By default, when you open the Catalog in your Standard account, all services with a Lite plan are displayed and 
identified with a Lite tag ![Lite tag](../icons/Lite.svg). Select a service to view the quota details for the associated Lite plan.

## Efficiency features
{: #devactivity}

To help you manage your resources, we included efficiency features that are based on development activity and usage.

### App auto sleep

Your apps will go to sleep after 10 days of development inactivity. This helps when you want to work on a new app, because you won’t find yourself hitting the 256 MB memory quota limit. 

To wake up your apps, start working on them again by using the {{site.data.keyword.Bluemix_notm}} console or the Cloud Foundry CLI. Here's a list of all commands that will wake up your app:
  * cf push
  * cf restate
  * cf restart
  * cf ssh
  * cf scale
  * cf stop
  * cf start
  * cf create-route
  * cf map-route
  * cf unmap-route
  * cf delete-route
  * cf enable-ssh
  * cf disable-ssh

For usage details, see [Cloud Foundry commands](/docs/cli/reference/cfcommands/index.html).

**Note**: If your app is already SSH enabled, you can't use the `cf enable-ssh` and `cf disable-sh` commands to wake up your app. 

### Garbage collection

Your Lite plan services are deleted if there isn’t any activity on them for 30 days. This means you don’t have to delete inactive instances when you want to create a new one. 
