# PromptPixie

**Category:** Creative & Design
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/019-promptpixie/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/019-promptpixie/)

## What it does

PromptPixie adapts one image idea into prompts for different generator families: it builds a platform-neutral master prompt, then translates it into each target tool's native grammar — natural-language, tag-friendly, or parameter-appended — noting what changed and why. Volatile syntax is flagged for checking; no artist names or dead tokens are used.

## متى يفيدك؟

يقوم PromptPixie بتكييف فكرة صورة واحدة في برومبتات لعائلات المولدات المختلفة: فهو ينشئ موجهًا رئيسيًا محايدًا للنظام الأساسي، ثم يترجمه إلى القواعد النحوية الأصلية لكل أداة مستهدفة - لغة طبيعية، أو صديقة للعلامات، أو ملحقة بالمعلمات - مع الإشارة إلى ما تغير ولماذا. يتم وضع علامة على بناء الجملة المتطاير للتحقق؛ لا يتم استخدام أسماء الفنانين أو الرموز الميتة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then an image generator that accepts text prompts.

**What to expect:** Describe the image and name your target generators (or let me cover the common families). You'll get a master prompt plus per-platform variants with short adaptation notes and negatives where supported.

## A useful first message

Create a vintage travel-poster concept for Alexandria at sunset, featuring the tram, sea, and historic buildings. Write a platform-neutral master prompt and versions adapted to different image-generator styles.

## طريقة البدء

قم بوصف الصورة وقم بتسمية المولدات المستهدفة (أو دعني أغطي العائلات المشتركة). ستحصل على مطالبة رئيسية بالإضافة إلى المتغيرات الخاصة بكل منصة مع ملاحظات التكيف القصيرة والسلبيات حيثما تكون مدعومة.

**مثال لرسالتك الأولى:**

أريد فكرة ملصق سفر قديم لمدينة الإسكندرية عند الغروب، فيها الترام والبحر ومبانٍ تاريخية. اكتب وصفًا أساسيًا ثم نسخًا مناسبة لقواعد أدوات توليد صور مختلفة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
