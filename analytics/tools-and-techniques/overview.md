---
layout: section
category: analytics
analytics_category: tools-and-techniques
title: Overview
weight: 1
---

# Tools and techniques

Rather than focus on specific types of business analysis, this section describes general purpose analytic techniques that can be used across many types of end-user analysis, including custom, catalog and platform analytics.

### 1. [Converting SnowPlow data into a format suitable for OLAP reporting tools e.g. Tableau, Qlikview] [convert-data-to-format-for-olap]

Many business intelligence tools treat data as a cube and enable analysts to slice, dice, drill down, roll up and pivot data sets across different dimensions. This type of analysis is typically called [OLAP] [olap], and is the main approach to reporting taken by a range of business intelligence tools including Tableau, Qlikview, Pentaho and Microstrategy.

In order to use OLAP reporting tools like Tableau and Qlikview, you need to restructure SnowPlow data from what is effectively a log file format (where each line represents one event that occured in a specific point of time) into a format suitable for OLAP analysis. (For this reason, you cannot run tools like Tableau and Qlikview directly on top of SnowPlow data.) In [this guide] [convert-data-to-format-for-olap], we explain what data structure is necessary for OLAP analysis, and how to quickly restructure SnowPlow data to enable the use of these tools.

### 2. [Using Mahout recommendation engines to deliver content or product recommendations with SnowPlow][recommendation]

Coming soon.

[convert-data-to-format-for-olap]: /analytics/tools-and-techniques/converting-snowplow-data-into-a-format-suitable-for-olap.html
[olap]: http://en.wikipedia.org/wiki/OLAP_cube
[recommendation]: /analytics/tools-and-techniques/using-mahout-recommendation-engines-to-deliver-content-or-product-recommendations-with-snowplow.html