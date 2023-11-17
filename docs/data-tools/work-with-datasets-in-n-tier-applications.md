---
title: Work with datasets in n-tier .NET Framework applications
description: Learn to work with datasets in n-tier .NET Framework applications in Visual Studio. N-tier data applications are data-centric apps that are separated into multiple logical layers (or tiers).
ms.date: 11/04/2016
ms.topic: conceptual
helpviewer_keywords:
- datasets [Visual Basic], n-tier applications
- multi-tier database applications
- DataSet project [VS n-tier applications]
- distributed applications [VS n-tier applications]
- data [Visual Basic], n-tier applications
- TableAdapters, n-tier applications
- n-tier applications
- tiers, n-tier applications
- typed datasets, n-tier applications
- multiple tier applications
author: ghogen
ms.author: ghogen
manager: jmartens
ms.technology: vs-data-tools
---
# Work with datasets in n-tier applications

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

[!INCLUDE [Data access tech note](./includes/data-technology-note.md)]

*N-tier data applications* are data-centric applications that are separated into multiple logical layers (or *tiers*). In other words, an n-tier data application is an application that is separated into multiple projects, with the data access tier, the business logic tier, and the presentation tier each in its own project. For more information, see [N-Tier data applications overview](../data-tools/n-tier-data-applications-overview.md).

Typed datasets have been enhanced so that the TableAdapters and dataset classes can be generated into discrete projects. This provides the ability to quickly separate application layers and generate n-tier data applications.

N-tier support in typed datasets enables iterative development of the application architecture to an n-tier design.It also removes the requirement to manually separate the code into more than one project. Start out designing the data layer by using the **Dataset Designer**. When you're ready to take the application architecture to an n-tiered design, set the **DataSet Project** property of a dataset to generate the dataset class into a separate project.

## Reference

- <xref:System.Data.DataSet>
- <xref:System.Data.TypedTableBase%601>

## Related content

- [N-Tier data applications overview](../data-tools/n-tier-data-applications-overview.md)
- [Walkthrough: Creating an n-tier Data Application](../data-tools/walkthrough-creating-an-n-tier-data-application.md)
- [Add code to TableAdapters in n-tier applications](../data-tools/add-code-to-tableadapters-in-n-tier-applications.md)
- [Add code to datasets in n-tier applications](../data-tools/add-code-to-datasets-in-n-tier-applications.md)
- [Add validation to an n-tier dataset](../data-tools/add-validation-to-an-n-tier-dataset.md)
- [Separate datasets and TableAdapters into different projects](../data-tools/separate-datasets-and-tableadapters-into-different-projects.md)
- [Hierarchical update](../data-tools/hierarchical-update.md)
- [Dataset tools in Visual Studio](../data-tools/dataset-tools-in-visual-studio.md)
- [Accessing data in Visual Studio](../data-tools/accessing-data-in-visual-studio.md)
- [Create and configure TableAdapters](../data-tools/create-and-configure-tableadapters.md)
- [N-Tier and remote applications with LINQ to SQL](/dotnet/framework/data/adonet/sql/linq/n-tier-and-remote-applications-with-linq-to-sql)
