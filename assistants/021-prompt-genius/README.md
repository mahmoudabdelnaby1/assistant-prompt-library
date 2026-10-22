# Prompt Genius

**Category:** Creative & Design  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/021-prompt-genius/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/021-prompt-genius/)

## What it does

Prompt Genius designs prompt systems, not just prompts: the prompt itself with template slots, a test suite including edge and adversarial cases, a scoring rubric with observable anchors, a failure taxonomy with patch strategies, and an iteration protocol. Systems are model-agnostic by default, with platform-specific parts clearly marked.

## متى يفيدك؟

تصمم Prompt Genius أنظمة سريعة، وليس مجرد برومبتات: الموجه نفسه مع فتحات القالب، ومجموعة اختبار تتضمن حالات الحافة والعداء، وقاعدة تقييم مع نقاط تثبيت يمكن ملاحظتها، وتصنيف الفشل مع استراتيجيات التصحيح، وبروتوكول التكرار. تعتبر الأنظمة مستقلة عن النموذج بشكل افتراضي، مع تحديد الأجزاء الخاصة بالمنصة بشكل واضح.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Describe the use case — what the prompt must do, for whom, and where it runs. You'll get the complete kit: engineered prompt, test suite, rubric, failure taxonomy, and iteration rules. Paste an existing prompt to systematize it.

## A useful first message

I want to use this assistant for its core task: Prompt Genius designs prompt systems, not just prompts: the prompt itself with template slots, a test suite including edge and adversarial cases, a scoring rubric with observable anchors, a failure taxonomy with patch strategies, and an iteration protocol. Systems are model-agnostic by default, with platform-specific parts clearly marked. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

قم بوصف حالة الاستخدام - ما الذي يجب أن يفعله الموجه، ولمن، وأين يتم تشغيله. ستحصل على المجموعة الكاملة: الموجه الهندسي ومجموعة الاختبار وقواعد التقييم وتصنيف الفشل وقواعد التكرار. قم بلصق موجه موجود لتنظيمه.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يصمم منظومات برومبت متكاملة قابلة لإعادة الاستخدام بدلًا من أمر منفرد. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
