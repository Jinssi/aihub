---
title: Azure AI Content Safety
date: 2023-11-16
description: >
  Used to keep your content safe. Create better online experiences for everyone with powerful AI models that detect offensive or inappropriate content in text and images quickly and efficiently.
categories: [Azure]
tags: [docs, content-safety, azure, ai, content, safety]
weight: 2
---

Azure AI Content Safety detects harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities.

Moderator works both for text and image content. It can be used to detect adult content, racy content, offensive content, and more. The service can be used to moderate content from a variety of sources, such as social media, public-facing communication tools, and enterprise applications.

* Language models analyze multilingual text, in both short and long form, with an understanding of context and semantics
* Vision models perform image recognition and detect objects in images using state-of-the-art Florence technology
* AI content classifiers identify sexual, violent, hate, and self-harm content with high levels of granularity
* Content moderation severity scores indicate the level of content risk on a scale of low to high

[Azure AI Content Safety Studio](https://contentsafety.cognitive.azure.com/) is an online tool designed to handle potentially offensive, risky, or undesirable content using cutting-edge content moderation ML models. It provides templates and customized workflows, enabling users to choose and build their own content moderation system. Users can upload their own content or try it out with provided sample content.

<video width="500" height="350" controls>
  <source src="https://cdn-dynmedia-1.microsoft.com/is/content/microsoftcorp/azure-ai-content-0x720-3266k" type="video/mp4">
  Your browser does not support the video tag.
</video>
 
**AI Hub** uses Azure AI Content Safety to moderate the content of the user's query, and to moderate the content of the response generated by our LLM (ChatGPT).

Learn more at the official documentation: [What is Azure AI Content Safety?](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/)