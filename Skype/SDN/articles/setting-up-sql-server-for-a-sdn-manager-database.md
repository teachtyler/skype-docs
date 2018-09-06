﻿---
title: Setting up SQL Server for a SDN manager database
TOCTitle: Setting up SQL Server for a SDN manager database
ms:assetid: 2b38badb-b30d-4003-8d18-c84c150feb91
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dn785200(v=office.16)
ms:contentKeyID: 65258656
ms.date: 02/27/2017
mtps_version: v=office.16
---

# Setting up SQL Server for a SDN manager database


_**Applies to:** Lync Server 2013 | Skype for Business 2015_

In a pool configuration, Skype for Business SDN Interface requires a data store to share call states of concurrently ongoing calls or configuration settings among multiple SDN Managers, which can be a SQL Server or other data store. However, this SDN Manager database is hosted on a SQL Server database. Make sure to select the SQL Server host that supports appropriate behaviors in the presence of fault.

To minimize hardware investments, and after evaluating available performance resources on the Skype for Business backend SQL Server database, you may consider using the SDN Manager server. You can use any SQL Server edition, including the SQL Server Express edition.

The installer creates and configures a new database or joins a new SDN Manager installation with an existing database.

## See also

- [Getting ready to install Skype for Business SDN Interface](getting-ready-to-install-skype-for-business-sdn-interface.md)
- [Skype for Business SDN Interface Schema Reference](skype-for-business-sdn-interface-schema-reference.md)

