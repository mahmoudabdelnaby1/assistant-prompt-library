# Pika Labs Prompter

**Category:** Coding & Technology  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/008-pika-labs-prompter/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/008-pika-labs-prompter/)

## What it does

Pika Labs Prompter designs multi-clip video prompt sequences that flow as one story: each clip is a single filmable beat, and a Continuity Bible — locked character descriptors, palette, and style anchor — repeats verbatim across clips so nothing drifts. Clip-length specifics are treated as tool-dependent and flagged, not hardcoded.

## متى يفيدك؟

يصمم Pika Labs Prompter تسلسلات فيديو سريعة متعددة المقاطع تتدفق كقصة واحدة: كل مقطع عبارة عن إيقاع واحد قابل للتصوير، ويتكرر الكتاب المقدس للاستمرارية - واصفات الشخصيات المقفلة، ولوحة الألوان، ومرساة النمط - حرفيًا عبر المقاطع حتى لا ينحرف أي شيء. يتم التعامل مع تفاصيل طول المقطع على أنها تعتمد على الأداة ويتم وضع علامة عليها، وليست مشفرة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then a video generator compatible with the output this assistant requests.

**What to expect:** Give me a theme and how many clips you want (a vibe helps). You'll get numbered paste-ready clip prompts, a continuity bible, the trailer narrative, and transition notes between clips.

## A useful first message

I am planning a three-shot vertical ad for a fictional café: grinding beans, pouring coffee, then serving the cup. Keep the cup and lighting consistent across shots and write a separate prompt for each scene.

## طريقة البدء

أعطني موضوعًا وعدد المقاطع التي تريدها (الأجواء تساعد). ستحصل على برومبتات مقطعية مرقمة وجاهزة للنسخ واللصق، وكتاب مقدس للاستمرارية، وسرد المقطع الدعائي، وملاحظات انتقالية بين المقاطع.

**مثال لرسالتك الأولى:**

أجهز إعلانًا عموديًا لمقهى افتراضي من 3 لقطات: طحن البن، صب القهوة، ثم تقديم الكوب. حافظ على شكل الكوب والإضاءة نفسها في كل لقطة، واكتب وصفًا منفصلًا لكل مشهد.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
