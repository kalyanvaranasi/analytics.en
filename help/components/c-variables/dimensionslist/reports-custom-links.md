---
description: Displays the links visitors to your site prefer. For example, the home page for your site likely has multiple links that display the same page. Perhaps there is both a graphic and text link that both link to the same page. This report shows what percentage of visitors used the graphic link versus the text link.
seo-description: Displays the links visitors to your site prefer. For example, the home page for your site likely has multiple links that display the same page. Perhaps there is both a graphic and text link that both link to the same page. This report shows what percentage of visitors used the graphic link versus the text link.
seo-title: Custom Link
solution: Analytics
title: Custom Link
topic: Reports
uuid: 2e0d0175-d5e4-4919-b601-3f488ef3e090
index: y
internal: n
snippet: y
---

# Custom Link

Displays the links visitors to your site prefer. For example, the home page for your site likely has multiple links that display the same page. Perhaps there is both a graphic and text link that both link to the same page. This report shows what percentage of visitors used the graphic link versus the text link.

The specific links that you would like to be tracked must be modified with special tags, see [Link Tracking](http://marketing.adobe.com/resources/help/en_US/sc/implement/?f=c_linktracking).

You can use the [!UICONTROL Custom Links Report] to:

* Optimize your site design by knowing which types of links your visitors prefer 
* Validate the need for redundant links to single pages

## Mobile SDK Link Names {#section_70C91FE794104B5FBF289B19CC02EA8E}

The [mobile SDKs](developer.md#concept_0151FC2D93434EE6BB3300D7F1A33E4A) use custom links to track actions and lifecycle metrics. In report suites that are used to measure mobile apps, you might see the following link names set by the SDK: 

|  ADBINTERNAL:Lifecycle  | Sent by the lifecycle call in the 4.x SDKs.  |
|---|---|
|  AMACTION:[action name]  | Sent by the trackAction() method in the 4.x SDKs, where action name is the name set when the method was called.  |
|  ADMS BP Event  | Sent by the lifecycle call in the 3.x SDKs.  |
