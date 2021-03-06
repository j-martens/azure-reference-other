---
title: "Error 0061 | Microsoft Docs"
titleSuffix: "Azure Machine Learning Studio"
ms.date: 07/19/2016
ms.service: "machine-learning"
ms.subservice: "studio"
ms.topic: "reference"

author: xiaoharper
ms.author: amlstudiodocs
manager: cgronlun
---
# Error 0061  
 Exception occurs when attempting to add a row to a DataTable that has a different number of columns than the table.  
  
 This error in Azure Machine Learning occurs when you attempt to add a row to a dataset that has a different number of columns than the dataset.  You will receive this error if the row that is being added to the dataset has a different number of columns from the input dataset.  The row cannot be appended to the dataset if the number of columns is different.  
  
## Resolution  
 Modify the input dataset to have the same number of columns as the row added, or modify the row added to have the same number of columns as the dataset.  
  
|Exception Messages|  
|------------------------|  
|All tables must have the same number of columns.|  
  
 > [!TIP]
 >  Need more help or troubleshooting tips for Azure Machine Learning? Try these resources:  
 >  
 >  -  [Troubleshooting guide: Create and connect to an Machine Learning workspace](https://azure.microsoft.com/documentation/articles/machine-learning-troubleshooting-creating-ml-workspace/)  
 >  -  [Azure Machine Learning Frequently Asked Questions (FAQ)](https://azure.microsoft.com/documentation/articles/machine-learning/studio/faq/)  
  
## See also  
 [Module error codes](../machine-learning-module-error-codes.md)
