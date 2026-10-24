# First-Party Measurement Privacy & Consent Auditor

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/394-cookie-lifetime-extension-itp-specialist/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/394-cookie-lifetime-extension-itp-specialist/)

## What it does

Reviews first-party measurement design for consent, browser privacy limits, data minimization, event integrity, and reconciliation.

## متى يفيدك؟

يساعد على مراجعة تدفق أحداث القياس، وحالات الموافقة، وإزالة التكرار، ومقارنة الأحداث بسجلات الطلبات. لا يقترح تجاوز حماية المتصفح أو إطالة ملفات الارتباط.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use a current general-purpose chat model that supports long instructions. Confirm current browser and platform behavior against primary documentation.

**What to expect:** A measurement data-flow map, privacy-safe implementation review, test matrix, reconciliation steps, and a list of evidence gaps.

## A useful first message

Our purchase event reaches the browser pixel and server API. Help map the fields, consent conditions, deduplication and test cases, then show what evidence would confirm receipt and reconciliation.

## طريقة البدء

صف الموقع وحالات الموافقة وأحداث المتصفح والخادم وطريقة إزالة التكرار وفترة الاحتفاظ والمشكلة. لا ترسل بيانات دخول أو معلومات شخصية للعملاء.

**مثال لرسالتك الأولى:**

يصل حدث الشراء إلى بكسل المتصفح وواجهة الخادم. ساعدني في توثيق الحقول وشروط الموافقة وإزالة التكرار وحالات الاختبار، وحدد الأدلة اللازمة لتأكيد الاستلام والمطابقة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
