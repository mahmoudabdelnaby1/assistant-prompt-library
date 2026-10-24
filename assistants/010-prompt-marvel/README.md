# Prompt Marvel

**Category:** General Assistants
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/010-prompt-marvel/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/010-prompt-marvel/)

## What it does

Prompt Marvel rebuilds prompts to professional standards. Paste any prompt for a scored diagnosis and a complete rewrite structured for reliable results — role, protocol, quality checks, output contract, and failure guards — with the rationale for each change. It can also engineer a prompt from scratch from a subject, purpose, and output format.

## متى يفيدك؟

يطالب Marvel الفوري بإعادة البناء وفقًا للمعايير المهنية. قم بلصق أي مطالبة للحصول على تشخيص مسجل وإعادة كتابة كاملة منظمة للحصول على نتائج موثوقة - الدور، والبروتوكول، وفحوصات الجودة، وعقد المخرجات، والوقاية من الفشل - مع الأساس المنطقي لكل تغيير. ويمكنه أيضًا تصميم مطالبة من البداية من الموضوع والغرض وتنسيق الإخراج.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Paste a prompt to rebuild, or describe what you need a prompt to do (subject, purpose, output format). You'll get the finished prompt in a copy block plus what changed and why.

## A useful first message

I want to use this assistant for its core task: Prompt Marvel rebuilds prompts to professional standards. Paste any prompt for a scored diagnosis and a complete rewrite structured for reliable results — role, protocol, quality checks, output contract, and failure guards — with the rationale for each change. It can also engineer a prompt from scratch from a subject, purpose, and output format. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

قم بلصق مطالبة لإعادة البناء، أو وصف ما تحتاج إلى مطالبة للقيام به (الموضوع، والغرض، وتنسيق الإخراج). ستحصل على المطالبة النهائية في كتلة نسخة بالإضافة إلى ما تغير ولماذا.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يراجع أي برومبت ويشخّص نقاط ضعفه ثم يعيد صياغته وفق معايير منظمة. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
