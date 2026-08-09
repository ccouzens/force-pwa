# Slack PWA

## How to install

> Note you will need chromium based browser to install this

Run the following code in the javascript console whilst on https://app.slack.com/

```javascript
const MANIFEST_URL =
  "https://raw.githubusercontent.com/ccouzens/slack-pwa/main/manifest.json";
const manifestLink = document.createElement("link");
manifestLink.rel = "manifest";
manifestLink.href = MANIFEST_URL;
document.head.appendChild(manifestLink);
```

Install as an app through the chrome UI.
