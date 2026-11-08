# Force PWA

Javascript snippets to configure particular websites for installation as an app.

## GlobalPlayer

Run the following code in the javascript console whilst on https://www.globalplayer.com/

```javascript
const MANIFEST_URL =
  "https://raw.githubusercontent.com/ccouzens/force-pwa/main/manifests/www.globalplayer.com.json";
const manifestLink = document.createElement("link");
manifestLink.rel = "manifest";
manifestLink.href = MANIFEST_URL;
document.head.appendChild(manifestLink);
```

Install as an app through the browser UI.

## Slack

Run the following code in the javascript console whilst on https://app.slack.com/

```javascript
const MANIFEST_URL =
  "https://raw.githubusercontent.com/ccouzens/force-pwa/main/manifests/app.slack.com.json";
const manifestLink = document.createElement("link");
manifestLink.rel = "manifest";
manifestLink.href = MANIFEST_URL;
document.head.appendChild(manifestLink);
```

Install as an app through the browser UI.
