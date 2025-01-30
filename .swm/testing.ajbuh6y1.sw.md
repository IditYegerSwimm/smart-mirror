---
title: testing
---
<SwmSnippet path="/scripts/script.js" line="13">

---

&nbsp;

```javascript
const getGridDetails = (url, rows, cols) => {

  if (isNaN(rows) || rows > 4 || rows < 1) {
    throw new Error("rows value must be a number between 1 to 4");
  }

  if (isNaN(cols) || cols > 4 || cols < 1) {
    throw new Error("Cols value must be a number between 1 to 4");
  }

  createNewDivs(rows, cols);
}
```

---

</SwmSnippet>

This doc is about the script.js file. In this file there is the getGridDetails function. This function, the getGridDetails function, has the variable rows in it. It also calls the function createNewDivs. The isNaN(rows) function checks is the rows variable is not a number.&nbsp;

<SwmLink doc-title="Test 2">[Test 2](/.swm/test-2.4dqcvbdd.pl.sw.md)</SwmLink>

## The <SwmToken path="/scripts/script.js" pos="23:1:1" line-data="  createNewDivs(rows, cols);">`createNewDivs`</SwmToken> function

The getElementById function is...&nbsp;

The clear-day clear-day is in the WEATHER_IMAGES&nbsp;

<SwmSnippet path="/scripts/CONSTS.js" line="1">

---

&nbsp;

```javascript
const WEATHER_IMAGES = {
  "clear-day": "images/sunny.png",
  "clear-night": "images/clear_night.png",
  "rain": "images/light_rain.png",
  "snow": "images/snow4.png",
  "sleet": "images/sleet.png",
```

---

</SwmSnippet>

<SwmToken path="/scripts/CONSTS.js" pos="2:2:4" line-data="  &quot;clear-day&quot;: &quot;images/sunny.png&quot;,">`clear-day`</SwmToken>

<SwmToken path="/scripts/CONSTS.js" pos="3:2:4" line-data="  &quot;clear-night&quot;: &quot;images/clear_night.png&quot;,">`clear-night`</SwmToken>

<SwmToken path="/scripts/CONSTS.js" pos="6:7:11" line-data="  &quot;sleet&quot;: &quot;images/sleet.png&quot;,">`images/sleet.png`</SwmToken>

<SwmToken path="/scripts/CONSTS.js" pos="2:9:11" line-data="  &quot;clear-day&quot;: &quot;images/sunny.png&quot;,">`images/sunny`</SwmToken>&nbsp;

&nbsp;

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBc21hcnQtbWlycm9yJTNBJTNBSWRpdFllZ2VyU3dpbW0=" repo-name="smart-mirror"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
