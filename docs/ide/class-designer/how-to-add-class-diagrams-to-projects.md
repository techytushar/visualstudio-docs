---
title: "How to: Add Class Diagrams to Projects (Class Designer) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "class diagrams, creating"
  - "Class Designer [Visual Studio], opening"
ms.assetid: 0eac1b54-2711-4e4b-9654-a0c429c08c8f
caps.latest.revision: 39
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
ms.workload: 
  - "multiple"
---
# How to: Add Class Diagrams to Projects (Class Designer)
To design, edit, and refactor classes and other types, add a class diagram to your C#, Visual Basic, or C++ project. To visualize different parts of the code in a project, add multiple class diagrams to the project.  
  
You can't create class diagrams from projects that share code across multiple apps. To create UML class diagrams, see [Create UML modeling projects and diagrams](../../modeling/create-uml-modeling-projects-and-diagrams.md).  
  
### To add a blank class diagram to a project  
  
1.  In Solution Explorer, right-click the project name. Then choose **Add New Item** or **Add**, **New Item**.  
  
2.  From the template list, choose the **Class Diagram**. For Visual C++ projects, look under **Templates**, and then under **Utility** to find this template.  
  
     The class diagram opens in Class Designer and appears as a file that has a .cd extension in Solution Explorer in the project hierarchy. Use the Class Designer toolbox to drag shapes and lines to the diagram.  
  
3.  To add multiple class diagrams, repeat the steps in this procedure.  
  
### To add a class diagram based on existing types  
  
1.  In Solution Explorer, open the class file context menu, then choose **View Class Diagram**.  
  
     -or-  
  
     In **Class View**, open the namespace or type context menu, then choose **View Class Diagram**.  
  
### To display the contents of a complete project in a class diagram  
  
1.  In Solution Explorer or Class View, right-click the project and choose **View**, then choose **View Class Diagram**.

     An auto-populated Class Diagram is created.  
  
## See also
[How to: Create Types by using Class Designer](how-to-create-types.md)   
[How to: View Existing Types](how-to-view-existing-types.md)   
[Designing Classes and Types](designing-classes-and-types.md)   
[Viewing Types and Relationships](viewing-types-and-relationships.md)   
[Working with Class Diagrams](working-with-class-diagrams.md)