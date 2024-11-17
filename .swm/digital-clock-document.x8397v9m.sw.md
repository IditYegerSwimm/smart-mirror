---
title: Digital Clock Document
---
This document explains about some of the functions in the <SwmPath>[scripts/components/digital-clock.js](/scripts/components/digital-clock.js)</SwmPath> file.

<SwmSnippet path="/scripts/components/digital-clock.js" line="3">

---

This code defines a function `displayDigitalClock` which receives a `cellNum` as an argument and uses it to get an element from the DOM. The function then clears the innerHTML of the `digitalClockElm`. It adds a class `digital-clock` to the `digitalClockElm`. Finally, it starts a clock by calling the function `startTime` with `digitalClockElm` as an argument.

```javascript
const displayDigitalClock = (cellNum) => {
  let digitalClockElm = document.getElementById(`div${cellNum}`);
  digitalClockElm.innerHTML = "";

  // Add digital clock style
  digitalClockElm.classList.add("digital-clock");

  // Start the clock
  startTime(digitalClockElm); 
}
```

---

</SwmSnippet>

<SwmSnippet path="/scripts/components/digital-clock.js" line="28">

---

This code defines a function `checkTime` that adds a leading zero to a given number `i` if it is less than 10, and returns the resulting value as a string.

```javascript
const checkTime = (i) => {
  // add zero in front of numbers < 10
  if (i < 10) {
    i = `0${i}`;
  }
  
  return i;
}
```

---

</SwmSnippet>

Cross-repo snippet

<SwmSnippet path="/HappyHippo.java" line="1" repo-id="Z2l0aHViJTNBJTNBaGFwcHktaGlwcG8lM0ElM0FJZGl0WWVnZXJTd2ltbQ==">

---

test

```java
class HappyHippo2 extends Hippo{
    public void feel() {
        System.out.println("I'm feeling happy!");
    }

    public void dance() {
        boolean happy = true;
        while (happy) {
            System.out.println("I'm dancing because I'm happy");
        }
    }
}

```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBc21hcnQtbWlycm9yJTNBJTNBSWRpdFllZ2VyU3dpbW0=" repo-name="smart-mirror"><sup>Powered by [Swimm](https://staging.swimm.cloud/)</sup></SwmMeta>
