---
id: sdk.widgetresettrigger
title: WidgetResetTrigger
hide_title: true
sidebar_class_name: sidebar-hidden
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@friendlycaptcha/sdk](./sdk.md) &gt; [WidgetResetTrigger](./sdk.widgetresettrigger.md)

## WidgetResetTrigger type

What caused the widget to reset. \* `root`<!-- -->: Code on the root page (= your website code or plugin) caused the reset. \* `widget`<!-- -->: The reset came from the widget. The user likely clicked the reset button within the widget. \* `agent`<!-- -->: The reset came from the agent - this currently does not happen but may in the future.

**Signature:**

```typescript
export type WidgetResetTrigger = "widget" | "root" | "agent";
```