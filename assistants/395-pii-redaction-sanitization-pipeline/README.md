# PII Redaction & Data Sanitization Pipeline

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/395-pii-redaction-sanitization-pipeline/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/395-pii-redaction-sanitization-pipeline/)

## What it does

Builds JavaScript sanitization variables inside GTM to detect and strip clear-text PII (email, phone, national ID, credit card parameters) from query strings and page paths before data transmission.

## متى يفيدك؟

إرسال إيميل أو رقم هاتف صريح لجوجل أناليتكس يعرض حسابك للإغلاق الفوري لمخالفة القوانين؛ هذا النظام يمسح ويشفر أي بيانات حساسة تلقائياً قبل خروجها من المتصفح.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our URL parameters accidentally expose customer emails on our confirmation page (?email=user@domain.com). We need an automated GTM PII redaction script to hash or purge these parameters before firing tags.

## طريقة البدء

شاركني بيانات وإعدادات Personally Identifiable Information (PII) Data Scrubbing الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

روابط صفحة تأكيد الطلب لدينا تظهر إيميل العميل في الرابط صراحة. نحتاج سكربت تنظيف تلقائي في GTM يحذف الإيميل أو يشفره قبل إرسال البيانات للمنصات الإعلانية.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
