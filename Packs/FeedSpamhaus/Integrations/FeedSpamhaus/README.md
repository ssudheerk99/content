## Overview
---

Use the Spamhaus feed integration to fetch indicators from the feed.


## Configure SpamhausFeed on Demisto
---

1. Navigate to __Settings__ > __Integrations__ > __Servers & Services__.
2. Search for SpamhausFeed.
3. Click __Add instance__ to create and configure a new integration instance.
    * __Name__: a textual name for the integration instance.
    * __Services__: Services of Spamhaus to fetch indicators from.
     * __Fetch indicators__: boolean flag. If set to true will fetch indicators.
    * __Fetch Interval__: Interval of the fetches.
    * __Reliability__: Reliability of the feed.  
    * __Skip Exclusion List__: When selected, the exclusion list is ignored for indicators from
    this feed. This means that if an indicator from this feed is on the exclusion
    list, the indicator might still be added to the system. 
    * __Indicator reputation__: Indicators from this integration instance will be marked with this
    reputation.
    * __Request Timeout__: Timeout of the polling request in seconds.
    * __Trust any certificate (not secure)__
    * __Use system proxy settings__
4. Click __Test__ to validate the URLs, token, and connection.
