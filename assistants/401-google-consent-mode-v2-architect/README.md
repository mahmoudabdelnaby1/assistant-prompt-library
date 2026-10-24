# Google Consent Mode v2 Basic vs Advanced Architect

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/401-google-consent-mode-v2-architect/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/401-google-consent-mode-v2-architect/)

## What it does

Implements Google Consent Mode v2 (ad_storage, ad_user_data, ad_personalization, analytics_storage), auditing the trade-offs between Basic (tags blocked) and Advanced (cookieless pings) modes.

## متى يفيدك؟

شرط إلزامي من جوجل لضمان استمرار عمل التتبع والاستهداف؛ يحدد هل تستخدم النمط الأساسي أو المتقدم الذي يرسل إشارات مجهولة لنمذجة التحويلات دون انتهاك خصوصية المستخدم.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our European and UK visitors must comply with Consent Mode v2 before March 2024. We need to implement Advanced Consent Mode in GTM with Cookiebot integration to preserve modeled conversions.

## طريقة البدء

شاركني بيانات وإعدادات Google Consent Mode v2 (Basic vs Advanced Execution) الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

نستقبل زواراً من أوروبا ونحتاج تطبيق Google Consent Mode v2 الإلزامي عبر GTM ومنصة Cookiebot لحماية حساب جوجل من الحظر واستعادة التحويلات المفقودة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
