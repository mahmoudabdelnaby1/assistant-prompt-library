# GA4 BigQuery Daily Export Schema & Cost Optimizer

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/406-ga4-bigquery-export-cost-optimizer/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/406-ga4-bigquery-export-cost-optimizer/)

## What it does

Configures the native GA4 to Google BigQuery export (Daily + Streaming), setting partition filters, table clustering by event_name, and query cost controls to run marketing SQL without massive cloud bills.

## متى يفيدك؟

جوجل أناليتكس العادي يحذف البيانات القديمة بعد 14 شهراً ويطبق تقريب الأرقام (Sampling)؛ ربطه بـ BigQuery يحفظ كل نقرة وحدث في قاعدة بياناتك الخاصة مدى الحياة لتحليلها بحرية.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

We want to connect our Shopify GA4 property to Google BigQuery for raw event warehousing, but we need partitioning rules so our daily analytical SQL queries don't cost hundreds of dollars.

## طريقة البدء

شاركني بيانات وإعدادات GA4 BigQuery Daily & Streaming Export Architecture الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

نريد ربط متجرنا بـ BigQuery لتخزين كل أحداث الزيارات الخام، مع وضع قواعد تقسيم الجداول لضمان تشغيل استعلامات SQL بتكاليف منخفضة جداً.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
