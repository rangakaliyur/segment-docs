---
title: FactorsAI Destination
rewrite: true
id: 5d1060c40d357d000181e92c
---
[FactorsAI](https://www.factors.ai/?utm_source=segmentio&utm_medium=docs&utm_campaign=partners) is a marketing analytics and revenue attribution platform purpose-built for B2B teams to decode the customer journey, improve marketing ROI, and drive revenue. Monitor and optimize your efforts and spend with comprehensive analytical functions, powerful conversion funnels, AI-fueled automated insights, and more across campaigns, website, MAP, CDP, & CRM.

This destination is maintained by FactorsAI. For any issues with the destination, [contact the FactorsAI Support team](mailto:support@factors.ai).

{% include content/beta-note.md %}

## Getting Started

{% include content/connection-modes.md %}

1. From the Segment web app, click **Catalog**.
2. Search for "FactorsAI" in the Catalog, select it, and choose which of your sources to connect the destination to.
3. Enter the "API Key" into your Segment Settings UI which you can find from your [FactorsAI dashboard](https://app.factors.ai/settings/integration).

## Page

If you're not familiar with the Segment Specs, take a look to understand what the [Page method](/docs/connections/spec/page/) does. An example call would look like:

```
factors.page()
```

Page calls will be sent to FactorsAI as an auto tracked `pageview`.


## Identify

If you're not familiar with the Segment Specs, take a look to understand what the [Identify method](/docs/connections/spec/identify/) does. An example call would look like:

```
factors.identify('userId123', {
  email: 'john.doe@example.com'
});
```

Identify calls will be sent to FactorsAI as an `identify` event.


## Track

If you're not familiar with the Segment Specs, take a look to understand what the [Track method](/docs/connections/spec/track/) does. An example call would look like:

```
factors.track('Product Viewed')
```

Track calls will be sent to FactorsAI as a `track` event.


## Screen

If you're not familiar with the Segment Specs, take a look to understand what the [Screen method](/docs/connections/spec/screen/) does. An example call would look like:

```
[[SEGAnalytics sharedAnalytics] screen:@"Home"];
```

Screen calls will be sent to FactorsAI as a track event with name `screenname`.


---
