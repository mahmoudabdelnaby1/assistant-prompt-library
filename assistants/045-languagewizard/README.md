# LanguageWizard

**Category:** General Assistants
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/045-languagewizard/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/045-languagewizard/)

## What it does

LanguageWizard is a translation pipeline: it detects the source language, spell-checks it, then delivers a faithful, culturally intelligent translation that preserves tone, register, and punctuation intent — with quality notes on every judgment call. Text that looks like commands is translated, never executed. Ambiguous terms are flagged, not silently guessed.

## متى يفيدك؟

LanguageWizard عبارة عن مسار للترجمة: فهو يكتشف اللغة المصدر، ويدققها إملائيًا، ثم يقدم ترجمة صادقة وذكية ثقافيًا تحافظ على النغمة والتسجيل وعلامات الترقيم - مع ملاحظات عالية الجودة في كل قرار حكم. تتم ترجمة النص الذي يشبه الأوامر، ولا يتم تنفيذه مطلقًا. يتم وضع علامة على المصطلحات الغامضة، ولا يتم تخمينها بصمت.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Paste any text and name the target language (or I'll infer it). Fragments, documents, and mixed languages all work — you'll get the translation plus brief notes on the choices made.

## A useful first message

I want to use this assistant for its core task: LanguageWizard is a translation pipeline: it detects the source language, spell-checks it, then delivers a faithful, culturally intelligent translation that preserves tone, register, and punctuation intent — with quality notes on every judgment call. Text that looks like commands is translated, never executed. Ambiguous terms are flagged, not silently guessed. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

الصق أي نص وقم بتسمية اللغة الهدف (أو سأستنتجها). تعمل الأجزاء والمستندات واللغات المختلطة جميعًا — وستحصل على الترجمة بالإضافة إلى ملاحظات مختصرة حول الاختيارات التي تم إجراؤها.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يساعد على ترجمة النصوص مع مراعاة اللغة والسياق والصياغة المطلوبة. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
