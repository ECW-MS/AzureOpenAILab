---
title: Introduction
layout: home
nav_order: 1
---

# AzureOpenAILab: Implementing automation practices using Azure OpenAI

This lab is based on the [TechExcel: Implementing automation practices using Azure OpenAI](https://microsoft.github.io/TechExcel-Implementing-automation-practices-using-Azure-OpenAI). It will be a slimmed down version of this two-day workshop.
In this lab you'll practice the skills required to build a full solution with Azure OpenAI that helps customers implement and adopt the solution. You'll engage with a real-world call centre scenario to become better prepared to build solutions. You’ll also gain insights into proven practices with customers and the best use of Azure OpenAI, Cosmos DB, Azure AI Search, and other Azure AI services.

## Learning Objectives

At the end of this workshop, you will be able to:

- Implement solutions leveraging Azure AI services, including Azure OpenAI, Cosmos DB, Azure AI Search, and other Azure AI services.
- Apply proven practices with customers in the use of the Azure AI services.  
- Describe use-cases for the Azure AI services to improve consumption of them.

## Prerequisites

For running this lab you will need:

- [Visual Studio Code](https://code.visualstudio.com/) installed on your device and the [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) and [Bicep](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep) extensions for Visual Studio Code. Alternatively, if you have Visual Studio installed, you can use that.
- [A Git client](https://git-scm.com/download/). An alternative option is to install [GitHub Desktop](https://desktop.github.com/).
- [Python 3.10 or later](https://www.python.org/downloads/). We recommend you install the [Anaconda distribution of Python](https://anaconda.com/download), though you can use a standard installation of Python. -- In the exercises, you may need to install additional packages. If you do not use the Anaconda distribution of Python, make sure that you can run `python` and `pip` from your command line. If you are not sure whether you have pip installed, run `python -m ensurepip` to check.
- Access to the **GitHub environment and Azure** resources before attending this workshop. In addition to access to Azure you need to **specifically request access to OpenAI Services within Azure**. To request access please complete the following form [Request Access to Azure OpenAI Service](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu). This should be granted within 24hrs.

![Request Form Sample](media/Instructions/0000_RequestOpenAIAccess-1.png)

To help prepare for the workshop, consider the following MS Learn content:

- Fundamentals of Azure AI services
- Fundamentals of Generative AI
- Microsoft Azure AI Fundamentals: AI Overview
- Fundamentals of Azure AI Speech
- Here is a [Collection](https://learn.microsoft.com/en-us/collections/jp5a6e530r0pe) of the learning paths mentioned above.

## Exercises

This lab has exercises on:

- Deploy app resources
- Add chat with data
- Implement function calls
- Implement audio transcription
- Provide live audio transcription
- Generate a call summary
