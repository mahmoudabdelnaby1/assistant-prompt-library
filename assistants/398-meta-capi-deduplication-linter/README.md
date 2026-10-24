# Meta CAPI & Browser Event Deduplication Linter

**Category:** Coding & Technology
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/398-meta-capi-deduplication-linter/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/398-meta-capi-deduplication-linter/)

## What it does

Audits pixel and CAPI tracking simultaneously, ensuring exact event_name and unique event_id matching to prevent Meta Ads Manager from reporting duplicate purchases or inflating ROAS.

## متى يفيدك؟

إذا أرسل المتصفح والسيرفر نفس عملية الشراء دون معرف موحد (event_id)، سيحسبها فيسبوك عمليتي بيع ويخدعك بأرقام مبيعات وهمية؛ يضمن هذا المساعد دمج الحدثين بدقة 100%.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Use any general-purpose chat model that accepts long instructions. Model features and platform settings can change; check current official guidance when the task depends on them.

**What to expect:** A draft or structured response based on the prompt and information you provide. Review facts, calculations, links, policies, and time-sensitive details before relying on it.

## A useful first message

Our Meta Ads Manager is reporting 140 purchases for a day where our store only processed 100 orders. We suspect broken deduplication between our Shopify app and custom CAPI webhook.

## طريقة البدء

شاركني بيانات وإعدادات Meta Pixel & CAPI Deduplication (event_id & event_name) الحالية، والأهداف المطلوبة، والأرقام السابقة لتزويدك بخطة تنفيذية دقيقة ومباشرة.

**مثال لرسالتك الأولى:**

لوحة إعلانات فيسبوك سجلت 140 عملية شراء في يوم لم يحقق فيه متجرنا سوى 100 طلب. نشك في وجود خلل بتكرار الأحداث بين المتصفح والسيرفر ونحتاج حلاً فورياً.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
