# Stable Diffusion Photography Prompts

**Category:** Writing & Storytelling  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/023-stable-diffusion-photography-prompts/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/023-stable-diffusion-photography-prompts/)

## What it does

Stable Diffusion Photography Prompts engineers portrait prompts for SD-class generators in two layers: a natural-language photographic core that works on any checkpoint, plus a compact tag layer you can adjust. Skin realism is built in (texture, asymmetry, catchlights), lighting follows one coherent story, and negative prompts never exclude what you asked for. No dead tokens or photographer names.

## متى يفيدك؟

التصوير الفوتوغرافي المنتشر الثابت يطالب المهندسين ببرومبتات الصور لمولدات فئة SD في طبقتين: قلب فوتوغرافي باللغة الطبيعية يعمل على أي نقطة تفتيش، بالإضافة إلى طبقة علامات مدمجة يمكنك ضبطها. تم بناء واقعية البشرة (الملمس، وعدم التناسق، والأضواء الساطعة)، وتتبع الإضاءة قصة واحدة متماسكة، ولا تستبعد البرومبتات السلبية أبدًا ما طلبته. لا توجد رموز ميتة أو أسماء المصورين.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then an image generator that accepts text prompts.

**What to expect:** Describe a subject, portrait mode (studio, environmental, documentary, fine-art), and mood. You'll get dual-layer prompts with paired negatives and the lighting logic explained in one line each.

## A useful first message

Create a documentary-style portrait of a potter in a workshop, with soft side light and natural depth of field. Provide a main prompt and a negative prompt for common visual artifacts.

## طريقة البدء

وصف الموضوع والوضع الرأسي (الاستوديو والبيئي والوثائقي والفنون الجميلة) والحالة المزاجية. ستحصل على برومبتات مزدوجة الطبقة مع صور سلبية مقترنة ومنطق الإضاءة موضح في سطر واحد لكل منهما.

**مثال لرسالتك الأولى:**

أريد بورتريه فوتوغرافيًا وثائقيًا لصانع فخار في ورشته، مع ضوء جانبي ناعم وعمق ميدان طبيعي. اقترح وصفًا رئيسيًا وقائمة عناصر سلبية تمنع التشوهات الشائعة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
