---
title: "include file"
description: "include file"
services: storage
author: tamram
ms.service: storage
ms.topic: "include"
ms.date: 09/15/2018
ms.author: tamram
ms.custom: "include file"
---

> [!IMPORTANT]
> Your storage account key is similar to the root password for your storage account. Always be careful to protect your account key. Avoid distributing it to other users, hard-coding it, or saving it anywhere in plaintext that is accessible to others. Regenerate your account key using the Azure portal if you believe it may have been compromised.
> 
> SAS (Shared Access Signature) tokens are critical to protect just like the account access keys. While providing granularity SAS grants clients access to the resources in your storage account and should not be shared publicly. When sharing is required for troubleshooting reasons consider using a redacted version of any log files or deleting the SAS tokens (if present) from the log files, and make sure the screenshots don't contain the SAS information either.
> 
> Microsoft recommends using Azure Active Directory (Azure AD) authentication for your Blob and Queue storage applications (preview) when possible for enhanced security. For more information, see [Authenticate access to Azure blobs and queues using Azure Active Directory (preview)](https://docs.microsoft.com/azure/storage/common/storage-auth-aad).
