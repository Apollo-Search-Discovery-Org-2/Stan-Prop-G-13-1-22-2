# Chat Shown

### 

## Javascript Code
```js
window.dataLayer09876 = window.dataLayer09876 || [];;
dataLayer09876.push({ event_data: null });  // Clear the previous event_data object.;
dataLayer09876.push({
  "event": "chat_shown",
  "apollo_event": "Chat Shown",
    "event_data": {
        "chat_shown_proactive": <chat_shown_proactive>,
        "chat_shown_reactive": <chat_shown_reactive>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|chat_shown_proactive|boolean|Count of time the user earned a cart promotion \(e.g., smart shopping cart\).|TRUE, FALSE|||||||
|chat_shown_reactive|boolean|Count of time a cart promotion \(e.g., smart shopping cart\) is displayed to the user.|TRUE, FALSE|||||||




