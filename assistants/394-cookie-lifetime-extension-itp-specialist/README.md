# Cookie Lifetime Extension & ITP 2.3+ Specialist

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/394-cookie-lifetime-extension-itp-specialist/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/394-cookie-lifetime-extension-itp-specialist/)

## What it does

Implements true server-set HTTP-only Set-Cookie response headers to override Apple WebKit 24-hour and 7-day client-side JavaScript cookie capping, keeping return attribution intact.

## متى يفيدك؟

آبل تحذف كوكيز المتصفح بعد 7 أيام مما يجعل العميل الذي يشتري بعد أسبوعين يظهر كعميل جديد مجهول المصدر؛ هذا المساعد يثبت الكوكيز من السيرفر مباشرة لربط المبيعات بالحملة الأصلية بدقة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our average customer consideration cycle is 21 days, but Safari ITP caps our Google and Meta tracking cookies at 7 days. We need a server-side Set-Cookie architecture to preserve attribution.

## طريقة البدء

شاركني بيانات وإعدادات Apple WebKit ITP 2.3+ & First-Party Cookie Longevity الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

دورة الشراء لدى عملائنا تستغرق 3 أسابيع، لكن قيود آبل تحذف بيانات التتبع بعد أسبوع واحد. نحتاج كوكيز سيرفرية HTTP-only لضمان نسبة المبيعات لحملاتها الإعلانية بدقة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
