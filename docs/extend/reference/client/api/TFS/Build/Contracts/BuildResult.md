---
title: TFS/Build/Contracts BuildResult API | Extensions for Azure DevOps Services
description: Data representation of a build result.
ms.assetid: c02121da-7f2c-6d1c-3f11-badd2a52fb2c
ms.technology: devops-ecosystem
generated: true
author: chcomley
ms.topic: article
ms.author: chcomley
ms.date: 08/04/2016
---

# BuildResult

Module path: `TFS/Build/Contracts`

### Values

* `None` No result
* `Succeeded` The build completed successfully.
* `PartiallySucceeded` The build completed compilation successfully but had other errors.
* `Failed` The build completed unsuccessfully.
* `Canceled` The build was canceled before starting.
