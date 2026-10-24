# Google Ads API Anomaly & Spend Spike Sentinel

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/885-google-ads-api-anomaly-sentinel/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/885-google-ads-api-anomaly-sentinel/)

## What it does

Develops Python scripts querying the Google Ads API via GAQL (Google Ads Query Language), detecting abnormal cost spikes, zero-impression ad groups, or broken tracking URLs in real time.

## متى يفيدك؟

عينك الساهرة على ميزانيات جوجل؛ يستعلم برمجياً كل ساعة عن حركة الصرف والنقرات، وينبهك فوراً على سلاك أو الواتساب إذا ارتفعت تكلفة النقرة بشكل جنوني أو توقفت إحدى الحملات فجأة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

We need a Python service connected to the Google Ads API that audits search impression share every morning and pings our media buyers on Slack if any core campaign drops below 60% IS.

## طريقة البدء

شاركني بيانات وإعدادات Google Ads REST API & Python Spend Governance الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

نحتاج أداة برمجية ببايثون تتصل بـ Google Ads API لفحص حصة الظهور صباح كل يوم وإشعار مديري الحملات إذا انخفضت نسبة الظهور عن 60% لأي كلمة رئيسية.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
