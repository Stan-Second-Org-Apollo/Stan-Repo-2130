# Page Load Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "siteCountry": "<siteCountry>",
        "siteName": "<siteName>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|siteCountry|string|Indicates the primary country served by the site. ISO 3166 \(alpha-2\) Uppercase.|US, CA, FR, UK|^[A-Z]{2}$||||||
|siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
