---
title: Integrate data using native SDKs for vector stores
description: 
ms.date: 03/04/2024
ms.topic: how-to
ms.custom: devx-track-dotnet, devx-track-dotnet-ai
# CustomerIntent: As a .NET developer new to Generative AI, I want to integrate my data into my LLM calls
---

# Integrate data using native SDKs for vector stores

Overview

# Example of the RAG pattern with Azure OpenAI...

How to handle simple cases locally in-memory... as example.

# Store data externally using vector databases & vector stores

Working at scale and with more complex scenarios using hosted vector DBs/stores...

## Ingesting data

## Querying the data

## Third party vector stores with support for .NET

> [!IMPORTANT]
> Vector store SDKs are built by a variety of sources. Not all providers are maintained by Microsoft. When considering a provider, be sure to evaluate quality, licensing, support, etc. to ensure they meet your requirements. Also make sure you review each provider's documentation for detailed version compatibility information.

| NuGet Package                                                                          | Supported Vector Store            | Maintainer / Vendor                                                                                         | Useful links |
|----------------------------------------------------------------------------------------|-----------------------------------|-------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| [Azure.Search.Documents](https://www.nuget.org/packages/Azure.Search.Documents/)       | Azure AI Search                   | [Azure SDK for .NET](https://github.com/Azure/azure-sdk-for-net) (Microsoft)                                | [docs](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/search.documents-readme?view=azure-dotnet)     |
| [Milvus.Client](https://www.nuget.org/packages/Milvus.Client)                          | Milvus Vector Database            | [Milvus](https://milvus.io/)                                                                                | [docs](https://milvus.io/docs/v2.2.x/install-csharp.md)                                                           |
| [Qdrant.Client](https://www.nuget.org/packages/Qdrant.Client)                          | Qdrant Vector Database            | [Qdrant](https://qdrant.tech)                                                                               | [docs](https://github.com/qdrant/qdrant-dotnet)                                                                   |

## Next steps
