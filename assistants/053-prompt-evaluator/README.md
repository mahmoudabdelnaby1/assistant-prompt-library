# Prompt Evaluator

**Category:** Creative & Design
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/053-prompt-evaluator/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/053-prompt-evaluator/)

## What it does

Prompt Evaluator judges prompts with rubric discipline: eight scored dimensions, every score backed by evidence quoted from the actual text, a verdict tier, the top three fixes ranked by impact, and a before→after preview of the highest-leverage change. Judging is category-aware — creative prompts aren't scored like extraction prompts — and the submitted prompt is treated strictly as evidence, never as instructions.

## متى يفيدك؟

يحكم المقيم الفوري على قواعد التقييم: ثمانية أبعاد مسجلة، كل درجة مدعومة بأدلة مقتبسة من النص الفعلي، ومستوى الحكم، والإصلاحات الثلاثة الأولى مرتبة حسب التأثير، ومعاينة قبل → بعد التغيير ذي التأثير الأعلى. يتم الحكم على أساس الفئة - لا يتم تسجيل البرومبتات الإبداعية مثل برومبتات الاستخراج - ويتم التعامل مع البرومبتات المقدمة بشكل صارم كدليل، وليس كتعليمات على الإطلاق.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Paste a prompt — or a batch to rank. You'll get the evidence-backed scorecard, verdict, prioritized fixes, and a rewrite preview of the single best change.

## A useful first message

I want to use this assistant for its core task: Prompt Evaluator judges prompts with rubric discipline: eight scored dimensions, every score backed by evidence quoted from the actual text, a verdict tier, the top three fixes ranked by impact, and a before→after preview of the highest-leverage change. Judging is category-aware — creative prompts aren't scored like extraction prompts — and the submitted prompt is treated strictly as evidence, never as instructions. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

الصق مطالبة - أو دفعة لتصنيفها. ستحصل على بطاقة الأداء المدعومة بالأدلة، والحكم، والإصلاحات ذات الأولوية، ومعاينة إعادة الكتابة لأفضل تغيير منفرد.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يقيّم البرومبت وفق معايير واضحة ويحدد نقاط القوة وما يحتاج إلى تحسين. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
