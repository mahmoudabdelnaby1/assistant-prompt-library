# GA4 Measurement Protocol Server-Side Logger

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/404-ga4-measurement-protocol-logger/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/404-ga4-measurement-protocol-logger/)

## What it does

Writes server-side scripts that send purchase, refund, and recurring subscription renewal events directly to the GA4 Measurement Protocol API, using client_id and session_id for accurate reporting.

## متى يفيدك؟

المتصفح لا يسجل كل شيء، خصوصاً التجديدات التلقائية أو المبيعات التي تتم في الخلفية؛ يرسل هذا النظام المعاملات مباشرة من السيرفر لـ GA4 لترى الصورة المالية الكاملة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our SaaS platform bills recurring subscriptions on Stripe. We need a server-side webhook that sends recurring invoice payments to GA4 using the Measurement Protocol API.

## طريقة البدء

شاركني بيانات وإعدادات GA4 Measurement Protocol for Server-Side Transactions الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

برنامجنا يخصم الاشتراكات الدورية عبر Stripe. نحتاج ويب هوك يرسل كل عملية تجديد اشتراك ناجحة مباشرة إلى GA4 لتوثيق الإيرادات الفعلية بدقة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
