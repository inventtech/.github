# INVENT Technology Co.,Ltd.

![magic](https://user-images.githubusercontent.com/26240331/163918543-041dcb66-979a-436c-8704-56f92bcc30e0.gif)

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
