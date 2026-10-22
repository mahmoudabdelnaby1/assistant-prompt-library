# Snippet Scribe

**Category:** Writing & Storytelling  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/108-snippet-scribe/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/108-snippet-scribe/)

## What it does

Snippet Scribe is a long-to-short transcript surgeon: paste a long-video transcript and it extracts and re-engineers standalone shorts of 100–300 words — complete sentences only, hook-restructured (your strongest line moves first), context-tested for viewers who never saw the long video — each with a title suggestion, source location, and standalone note. Your words are preserved faithfully: reordering and marked trims only, never rewriting, never invented content.

## متى يفيدك؟

Snippet Scribe عبارة عن جراح نص طويل إلى قصير: قم بلصق نص فيديو طويل ويستخرج ويعيد هندسة المقاطع القصيرة المستقلة التي تتراوح من 100 إلى 300 كلمة - جمل كاملة فقط، معاد هيكلتها (أقوى سطر يتحرك أولاً)، تم اختبار السياق للمشاهدين الذين لم يشاهدوا الفيديو الطويل مطلقًا - كل منها مع اقتراح عنوان، وموقع المصدر، وملاحظة مستقلة. يتم الحفاظ على كلماتك بأمانة: إعادة الترتيب والتشطيبات المميزة فقط، عدم إعادة الكتابة مطلقًا، عدم اختراع المحتوى مطلقًا.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Paste your transcript (any length that fits) and how many shorts you want. You'll get the snippet library with titles, source locations, and a coverage note on what remains for batch two.

## A useful first message

I want to use this assistant for its core task: Snippet Scribe is a long-to-short transcript surgeon: paste a long-video transcript and it extracts and re-engineers standalone shorts of 100–300 words — complete sentences only, hook-restructured (your strongest line moves first), context-tested for viewers who never saw the long video — each with a title suggestion, source location, and standalone note. Your words are preserved faithfully: reordering and marked trims only, never rewriting, never invented content. My project or topic is [context], the audience is [audience], and the outcome I need is [goal]. Use only the details I provide and ask about essential missing information.

## طريقة البدء

الصق نصك (أي طول يناسبك) وعدد السراويل القصيرة التي تريدها. ستحصل على مكتبة المقتطفات التي تحتوي على العناوين ومواقع المصادر ومذكرة تغطية حول ما تبقى للدفعة الثانية.

**مثال لرسالتك الأولى:**

أريد استخدام هذا المساعد في مهمته الأساسية: يختصر النصوص والتفريغات الطويلة إلى مقاطع موجزة مع الحفاظ على الفكرة. أعمل على [مشروعي أو موضوعي]، والجمهور [الفئة]، والنتيجة التي أحتاجها [الهدف]. استخدم التفاصيل التي سأرسلها فقط، واسألني عن أي معلومة أساسية ناقصة.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
