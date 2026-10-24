# Imagi Magician

**Category:** Creative & Design
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/011-imagi-magician/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/011-imagi-magician/)

## What it does

Imagi Magician writes engineered image prompts for Leonardo-style and other generators in two modes: photorealistic (subject detail → type → style → camera → shot → lighting → render feel) and artistic (medium → subject → movement/style → technique → finish). Quality tokens are used sparingly; inspirations are movements and mediums, not living artists; weighting syntax is flagged as tool-dependent.

## متى يفيدك؟

يكتب Imagi Magician برومبتات صور هندسية لأسلوب ليوناردو والمولدات الأخرى في وضعين: واقعي (تفاصيل الموضوع ← النوع ← النمط ← الكاميرا ← اللقطة ← الإضاءة ← إحساس العرض) والفني (متوسط ​​← الموضوع ← الحركة/الأسلوب ← التقنية ← النهاية). يتم استخدام رموز الجودة بشكل مقتصد؛ الإلهامات هي حركات ووسائط، وليست فنانين أحياء؛ يتم وضع علامة على بناء جملة الترجيح على أنه يعتمد على الأداة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then an image generator that accepts text prompts.

**What to expect:** Give me a theme or subject — and a mode if you have a preference (photorealistic, artistic, or both). You'll get paste-ready prompts with rationale, variation options, and negative-prompt suggestions where relevant.

## A useful first message

Create an ad image for a reusable steel water bottle with a natural background and morning light. Give me one photorealistic and one illustrated direction, each as a ready-to-use image prompt.

## طريقة البدء

أعطني سمة أو موضوعًا - ووضعًا إذا كان لديك تفضيل (صورة واقعية، أو فنية، أو كليهما). ستحصل على برومبتات جاهزة للنسخ واللصق تتضمن الأساس المنطقي وخيارات التباين واقتراحات المطالبة السلبية حيثما كان ذلك مناسبًا.

**مثال لرسالتك الأولى:**

أريد صورة إعلانية لزجاجة مياه قابلة لإعادة الاستخدام مصنوعة من الفولاذ، بخلفية طبيعية وإضاءة صباحية. قدّم خيارًا واقعيًا وآخر بأسلوب توضيحي، مع وصف جاهز لتوليد الصورة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
