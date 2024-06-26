---
title: Enrich Sales lead summaries with an insight from Customer Insights – Data (preview)
description: Discover how Customer Insights - Data generates content to the lead summary in Dynamics 365 Sales.
author: radsay01
ms.author: rsayyaparaju 
ms.reviewer: v-wendysmith
ms.topic: conceptual
ms.date: 04/29/2024
ms.custom: bap-template
---

# Enrich Sales lead summaries with an insight from Customer Insights – Data (preview)

[!INCLUDE [public-preview-banner](includes/public-preview-banner.md)]

Dynamics 365 Sales users can enrich their lead summary with an insight from Customer Insights - Data. The insight is based on unified activity data ingested by the user, such as customer reviews, purchases, appointments, web logs, and more. The insight is an observation of one of the following characteristics:

- **Customer's sentiment**: Their attitudes or feelings toward the business and their products or services.
- **Customer's behavior**: The cadence of their activities such as time intervals between appointments.
- **Customer's interest**: How likely they're to do something such as schedule an appointment or purchase a specific type of product.

Leveraging unified activity data from Customer Insights - Data to add an insight to the [lead summary in Dynamics 365 Sales](/dynamics365/sales/copilot-get-information#enrich-leads-with-related-information) helps sellers understand more about their lead, without leaving their workflow. Sellers can spend less time manually parsing through multiple data sources to find and synthesize information about their leads, and more time having effective conversations with them.

[!INCLUDE [public-preview-note](includes/public-preview-note.md)]

## Requirements

- Both apps are on the same Dataverse environment.
- [Enabled Copilot consent](copilot-global-consent.md).
- [Ingested data sources](data-sources.md).
- [Unified customer profile](data-unification.md).
- [Configured index filters](search-filter-index.md) includes customer's FirstName and LastName (or FullName), and Email.
- [Defined customer activities](activities.md) for the insights you want. For best results, define the following activity fields:
  - **Timestamp**: Date and time of the activity allowing customer profile summary to analyze the frequency and cadence of your customers’ engagement.
  - **Additional detail**: Detailed information about the activity. For example, if you want insights about customers’ sentiment through their reviews, include **ReviewText** or **Rating**. The more context provided, the better your results. Text values or a combination of text and numerical values produce higher quality results than numerical only values.

## Next steps

- [Responsible AI FAQs for customer insights in Sales lead summaries (preview)](faqs-profile-summary.md)
- [Responsible AI FAQs for Customer Insights - Data](responsible-ai-overview.md)
