# Cloudflare Worker Custom Loader for GTM & GA4

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/392-cloudflare-worker-custom-loader-gtm/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/392-cloudflare-worker-custom-loader-gtm/)

## What it does

Deploys Cloudflare Worker reverse proxies that rewrite and serve GTM and GA4 scripts under disguised first-party filenames, completely bypassing Brave, uBlock Origin, and DNS-level ad blockers.

## متى يفيدك؟

برامج حجب الإعلانات تحجب أي ملف اسمه gtm.js تلقائياً؛ يقوم هذا العامل السحابي بإعادة تسمية الكود ديناميكياً ليظهر كأنه ملف برمجي عادي من موقعك، مما يضمن وصول 100% من بيانات التحويلات.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our tech B2B SaaS website visitors heavily use uBlock Origin. We need a Cloudflare Worker script that proxies GTM and GA4 requests through an arbitrary custom endpoint like /cdn-cgi/v-lib.js.

## طريقة البدء

شاركني بيانات وإعدادات Cloudflare Workers & Custom Reverse-Proxy Tag Loaders الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

زوار موقعنا البرمجي يستخدمون مانع الإعلانات بكثافة. نحتاج كود Cloudflare Worker يحمل أكواد التحليلات عبر رابط خفي داخل موقعنا لتسجيل التحويلات بالكامل.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
