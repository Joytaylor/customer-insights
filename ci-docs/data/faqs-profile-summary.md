---
title: FAQs for customer insights in Sales lead summaries (preview)
description: This FAQ provides information about the AI technology used in Customer Insights - Data to Dynamics 365 Sales (preview). 
ms.date: 04/29/2024
ms.custom: 
  - responsible-ai-faqs
ms.topic: overview
author: radsay01
ms.author: rsayyaparaju 
ms.reviewer: mhart
---

# FAQ for customer insights in Sales lead summaries (preview)

[!INCLUDE [public-preview-banner](includes/public-preview-banner.md)]

These frequently asked questions (FAQs) detail how AI technology plays a role in delivering the lead summaries in Dynamics 365 Sales (preview).

[!INCLUDE [public-preview-note](includes/public-preview-note.md)]

## What are customer insights in Sales lead summaries?

Customer insights are AI-generated content designed to help sellers make better decisions about how to engage and interact with their customer. The insight appears on the Dynamics 365 Sales’ lead summary when the seller asks Sales Copilot (preview) to summarize a lead.

## What are the feature’s capabilities?

The feature takes available information from customer activities and generates insights that are available in Dynamics 365 Sales. This data helps sellers understand how a customer is engaging with their business. Sellers can use this information, paired with their own business understanding, to engage a user with a personalized experience.

The feature uses information from the customer’s activity stream and performs analysis on the data using Azure OpenAI capabilities. You can view Azure OpenAI data privacy policies here: [Data, privacy, and security for Azure OpenAI Service - Azure AI services | Microsoft Learn](/legal/cognitive-services/openai/data-privacy)

## What is the feature’s intended use?

The insight is intended to help sellers understand more about what a customer does, such as how frequently the customer engages with their business, and enable sellers to better customize their interactions with the customer.

## How is the feature evaluated? What metrics are used to measure performance?

This feature is currently evaluated only in English.

The feature is evaluated from dimensions of accuracy of response and quality of insight. Specifically, this feature is tested with an array of scenarios to ensure it captures content that is inappropriate, illegal or a manipulation of data.

## What are the limitations of the feature? How can users minimize the impact of the feature limitations when using the system?

The feature only analyzes information for a single customer at a time. The system reviews a subset of the customer's activities, ordered by date, and identifies insights from the information to help sellers better understand how the customer engages with their business. To create better insights, add more activity information for your customers.

## What are the supported geographies and languages?

The feature is available in the United States and supports English only.

## What operational factors and settings allow for effective and responsible use of the feature?

- Administrators in Customer Insights - Data can choose to disable all Copilot functionality for each solution, by using the [consent experience](copilot-global-consent.md).

- Similarly an Administrator in the Sales application can [disable the use of Customer Insights - Data](/dynamics365/sales/enable-setup-copilot#enable-or-disable-copilot-features-in-dynamics-365-apps).

- In general, you should use the feature in a mindful way to ensure responsible and appropriate inputs and outputs to minimize bias and unfairness.

## See also

- [Enrich Sales lead summaries with an insight from Customer Insights – Data (preview)](lead-profile-summary.md)