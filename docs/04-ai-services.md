---
sidebar_label: 'AI Services'
slug: /ai-services
---

# AI Services 

## Foundation Models

A key component of AI services is the foundation model. A foundation model is an AI system trained on large datasets to handle various tasks. Once trained, it can process new data to make decisions and generate content. 

For example, models trained on text can understand and generate human language by identifying patterns in words, content, and grammar. 

There are two types of foundation models: large language models, which require significant computing resources and run in the cloud, and smaller models, which can run efficiently on devices with lower processing power.
 
## Search

AI services include search, and there are two types: keyword search and semantic search. 

Keyword search looks for exact matches of words, whereas semantic search understands meaning and context. For example, if you search “how does global warming impact nature?” a keyword search would look for exact matches of those words, while semantic search would understand the intent and also match phrases like “rising temperatures harming wildlife.”

The technology behind semantic search is called embeddings

## Embeddings / Vectors

We usually think in 2D or 3D space with X, Y, and Z axes, but embeddings take complex data and convert it into high-dimensional vectors, sometimes with hundreds of thousands of dimensions. 

For example, the phrase “how do I fix my phone screen?” is converted into a numerical vector. A similar phrase, “how do I repair a broken phone screen?” produces a vector with close values, while an unrelated phrase like “what is the weather like today?” results in a very different vector. In real-world applications, embeddings often contain around 1,500 numbers to define meaning.

Embeddings are also used in medical imaging. An X-ray can be converted into a vector, and conditions such as chest diseases tend to cluster together in vector space. This allows AI to analyze new X-rays and predict conditions based on similarities in the embedding space.

Vector storage is where these embeddings are kept, with solutions like AI Search, Redis, and Cosmos DB enabling fast searches against them.

## Cognitive services 

Cognitive services are cloud-based APIs that allow developers to integrate AI into apps without requiring AI expertise. For example, developers can use pre-built services for language translation, image recognition, facial analysis, and speech processing.   

Azure offers a portflio of such cognitive services.
