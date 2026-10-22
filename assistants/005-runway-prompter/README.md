# Runway Prompter

**Category:** Creative & Design  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/005-runway-prompter/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/005-runway-prompter/)

## What it does

Runway Prompter writes text-to-video prompts using practical film language: one continuous action per clip, shot type and angle, subject and setting, lighting, and camera movement. For sequences it adds a continuity bible — locked character, palette, and style lines — so clips cut together without drift. Platform-specific controls are marked as current-syntax dependent.

## متى يفيدك؟

يكتب Runway Prompter برومبتات تحويل النص إلى فيديو باستخدام لغة الفيلم العملية: إجراء واحد مستمر لكل مقطع، ونوع اللقطة وزاويتها، والموضوع والإعداد، والإضاءة، وحركة الكاميرا. بالنسبة للتسلسلات، فإنه يضيف استمرارية - أحرف مقفلة، ولوحة ألوان، وخطوط نمط - بحيث يتم قص المقاطع معًا دون انحراف. يتم وضع علامة على عناصر التحكم الخاصة بالنظام الأساسي على أنها تعتمد على بناء الجملة الحالي.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then a video generator compatible with the output this assistant requests.

**What to expect:** Describe a scene or a sequence idea. I'll return shot-ready prompts — one clean action beat per clip — plus camera and lighting notes, and a continuity block if you're building multiple shots.

## A useful first message

I am planning a 10-second vertical ad for a fictional café. Create one continuous shot that starts with coffee being poured and ends with the cup on the table, using warm morning light and a gentle camera move. Write a prompt for a video generator.

## طريقة البدء

وصف مشهد أو فكرة التسلسل. سأعيد لك برومبتات جاهزة للتصوير - حركة واضحة واحدة لكل مقطع - بالإضافة إلى ملاحظات الكاميرا والإضاءة، وكتلة الاستمرارية إذا كنت تقوم بإنشاء لقطات متعددة.

**مثال لرسالتك الأولى:**

أجهز إعلانًا عموديًا مدته 10 ثوانٍ لمقهى افتراضي. أريد لقطة واحدة متصلة تبدأ بصب القهوة وتنتهي بظهور الكوب على الطاولة، بإضاءة صباحية دافئة وحركة كاميرا هادئة. اكتب وصفًا أستخدمه في أداة توليد فيديو.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
