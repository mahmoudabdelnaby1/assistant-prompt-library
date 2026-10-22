# Extension Xpert

**Category:** Coding & Technology  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/096-extension-xpert/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/096-extension-xpert/)

## What it does

Extension Xpert turns plain-language requests into complete browser-extension code: every file delivered in full (manifest, logic, popup, content scripts), minimal permissions each justified, security-first patterns (no remote code, safe DOM handling), current manifest standards noted for verification before store submission, plus step-by-step install and test instructions. Code is traced line by line before delivery — not executed here, and never claimed as tested.

## متى يفيدك؟

يحول ملحق Xpert طلبات اللغة البسيطة إلى كود ملحق متصفح كامل: يتم تسليم كل ملف بالكامل (البيان والمنطق والنوافذ المنبثقة والنصوص البرمجية للمحتوى)، والحد الأدنى من الأذونات المبررة لكل منها، وأنماط الأمان أولاً (بدون تعليمات برمجية عن بعد، والتعامل الآمن مع DOM)، ومعايير البيان الحالية المذكورة للتحقق قبل تقديم المتجر، بالإضافة إلى تعليمات التثبيت والاختبار خطوة بخطوة. يتم تتبع التعليمات البرمجية سطرًا تلو الآخر قبل التسليم - ولا يتم تنفيذها هنا، ولم تتم المطالبة بها مطلقًا على أنها تم اختبارها.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Describe what you want in plain words — "a button that darkens any page", "count words on every article". You'll get the full working code, permissions justified, install steps, and two next-feature ideas.

## A useful first message

I want a browser extension that saves article links to a local reading list. Explain the simplest architecture and required permissions, then sketch a prototype without unnecessary permissions.

## طريقة البدء

قم بوصف ما تريده بكلمات واضحة - "زر يظلم أي صفحة"، "عد الكلمات في كل مقال". ستحصل على رمز العمل الكامل والأذونات المبررة وخطوات التثبيت وفكرتين للميزات التالية.

**مثال لرسالتك الأولى:**

أريد إضافة متصفح تحفظ روابط المقالات في قائمة قراءة محلية. اشرح أبسط بنية للامتداد والصلاحيات المطلوبة، ثم اعرض نموذجًا أوليًا ولا تطلب صلاحيات لا يحتاجها.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
