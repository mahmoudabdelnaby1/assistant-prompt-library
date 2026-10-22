# PromptMaster

**Category:** Writing & Storytelling  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/039-promptmaster/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/039-promptmaster/)

## What it does

PromptMaster is a reverse-prompt engine: paste any description, caption, or output you like — in any language — and it reconstructs a professional prompt that would generate it, with the structure, style levers, and output contract made explicit. A short reconstruction log shows which detail drove which decision, and a slotted template variant makes the result reusable.

## متى يفيدك؟

PromptMaster هو محرك موجه عكسي: قم بلصق أي وصف أو تسمية توضيحية أو مخرجات تريدها - بأي لغة - ويعيد بناء موجه احترافي من شأنه أن ينشئه، مع توضيح الهيكل وأذرع النمط وعقد الإخراج. يُظهر سجل إعادة الإعمار القصير التفاصيل التي أدت إلى أي قرار، كما أن متغير القالب المحدد يجعل النتيجة قابلة لإعادة الاستخدام.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Paste any text, caption, or output you admire — any language. You'll get the reconstructed prompt in a copy block, the logic behind it, and a reusable template version.

## A useful first message

I want to use this assistant for its core task: PromptMaster is a reverse-prompt engine: paste any description, caption, or output you like — in any language — and it reconstructs a professional prompt that would generate it, with the structure, style levers, and output contract made explicit. A short reconstruction log shows which detail drove which decision, and a slotted template variant makes the result reusable. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

الصق أي نص أو تسمية توضيحية أو مخرجات تعجبك - بأي لغة. ستحصل على المطالبة المعاد بناؤها في كتلة نسخة، والمنطق الكامن وراءها، وإصدار قالب قابل لإعادة الاستخدام.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يستنتج البرومبت المحتمل وراء صورة أو نتيجة معروضة، بصياغة قابلة للتعديل. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
