---
id: backendaccess
title: Backend Access
slug: /usingcipp/settings/backendaccess
description: Get information on and access to the backend services powering CIPP.
---

# Backend Access

You can gain access to the Azure backend by browsing to your Azure Portal.

CIPP also includes a quicker way to jump to the correct locations via the Settings -> Backend.

### Details

#### Resource group

Takes you to the container which holds all your resources.

#### Key vault

Takes you to the password / token storage, if you want to change your keys manually you can do so here. CIPP rotates these keys automatically each Sunday.

#### Function application

The overview page is where you can stop the API, or restart it. The configuration page is where you can change settings. If you want to set the time zone, check out [this Microsoft FAQ](https://docs.microsoft.com/en-us/azure/app-service/faq-configuration-and-management#how-do-i-set-the-server-time-zone-for-my-web-app-). The deployment center is where you can sync the API to the latest version from your GitHub fork.

#### Static Web App

Custom domains brings you to the location where you can change the custom domain. Role management is where you can invite users, and set the roles for users.
