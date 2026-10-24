# Render Gen

**Category:** Creative & Design
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/036-render-gen/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/036-render-gen/)

## What it does

Render Gen writes 3D-render-style image prompts using real render language: material physics (subsurface scattering, metalness, caustics), studio and HDRI-style lighting setups, render-camera logic, and controlled imperfection for believability — across product viz, archviz, characters, isometric dioramas, and motion-graphics frames. Engine quality is described as a class, never pinned to versions; resolution-tag spam is avoided.

## متى يفيدك؟

يكتب Render Gen برومبتات صور بنمط العرض ثلاثي الأبعاد باستخدام لغة العرض الحقيقية: فيزياء المواد (التشتت تحت السطح، والمعادن، والمواد الكاوية)، وإعدادات الإضاءة على نمط الاستوديو وHDRI، ومنطق عرض الكاميرا، والعيوب التي يتم التحكم فيها من أجل المصداقية - عبر المنتج، والأرشفيز، والشخصيات، والديوراما متساوية القياس، وإطارات الرسومات المتحركة. يتم وصف جودة المحرك على أنها فئة، ولا يتم تثبيتها مطلقًا على الإصدارات؛ يتم تجنب البريد العشوائي الخاص بعلامة الدقة.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** A conversational text model, then an image generator that accepts text prompts.

**What to expect:** Tell me a subject and a render mode (product, archviz, character, isometric, abstract). You'll get paste-ready prompts with material and lighting logic explained, plus negatives and variation options.

## A useful first message

Create a 3D render concept for a minimalist ceramic desk lamp. Show material, shadow, and reflections on a neutral background, with useful angles for a product page.

## طريقة البدء

أخبرني بالموضوع ووضع العرض (المنتج، الأرشيف، الشخصية، متساوي القياس، الملخص). ستحصل على برومبتات جاهزة للنسخ واللصق مع شرح منطق المواد والإضاءة، بالإضافة إلى خيارات الصور السلبية والتنوع.

**مثال لرسالتك الأولى:**

أحتاج تصورًا ثلاثي الأبعاد لمصباح مكتبي من السيراميك بتصميم بسيط. أظهر الخامة والظل والانعكاس على خلفية محايدة، وقدّم زوايا عرض مناسبة لصفحة منتج.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
