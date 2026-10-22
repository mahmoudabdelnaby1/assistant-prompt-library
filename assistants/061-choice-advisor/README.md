# Choice Advisor

**Category:** General Assistants  
**Assistant page:** [English](https://mahmoudabdelnaby1.github.io/assistants/061-choice-advisor/) · [العربية](https://mahmoudabdelnaby1.github.io/ar/assistants/061-choice-advisor/)

## What it does

Choice Advisor is a decision engine: it frames the actual choice, extracts and weights the criteria that matter to you, scores each option with visible evidence and confidence marks, surfaces honest trade-offs and second-order effects, checks how reversible the decision is, then commits to a clear verdict with the pivotal assumption named. Prices and specs are never invented — unknowns are flagged for you to verify.

## متى يفيدك؟

Choice Advisor هو محرك اتخاذ القرار: فهو يضع إطارًا للاختيار الفعلي، ويستخرج المعايير التي تهمك ويزنها، ويسجل كل خيار بأدلة مرئية وعلامات ثقة، ويبرز المقايضات الصادقة وتأثيرات الدرجة الثانية، ويتحقق من مدى إمكانية عكس القرار، ثم يلتزم بحكم واضح مع الافتراض المحوري المذكور. لا يتم اختراع الأسعار والمواصفات مطلقًا، بل يتم وضع علامة على العناصر المجهولة لتتمكن من التحقق منها.

## Start using it

1. Open a new conversation in a general-purpose chat model that accepts long instructions. The specific model/tool guidance for this assistant is below.
2. Copy the full text from [`prompt.md`](prompt.md) into the model's instruction field, if available; otherwise paste it as the first message.
3. Send a separate task message. Adapt the example below with your real audience, context, facts, and constraints.
4. Review the output, especially facts, numbers, links, and time-sensitive claims, before using it.

**Suggested model/tool:** Any modern chat model that accepts long instructions, such as ChatGPT, Gemini, or Claude. No special model is required.

**What to expect:** Tell me the options you're weighing and what matters to you. You'll get a scored comparison, the honest trade-offs, a reversibility check, and one decisive recommendation with its reasoning.

## A useful first message

I am deciding between leasing a café space and starting with delivery only. Compare the options by cost, risk, and speed to test, then ask me for missing information before recommending one.

## طريقة البدء

أخبرني بالخيارات التي تزنها وما يهمك. سوف تحصل على مقارنة مسجلة، والمقايضات الصادقة، والتحقق من إمكانية الرجوع، وتوصية واحدة حاسمة مع منطقها.

**مثال لرسالتك الأولى:**

أفكر في الاختيار بين استئجار موقع لمقهى أو البدء بالتوصيل فقط. قارن البديلين وفق التكلفة والمخاطر وسرعة الاختبار، ثم اسألني عن المعلومات الناقصة قبل التوصية.

## Prompt language and runtime

The full prompt is provided in its original language. This repository contains reusable instructions; it does not host or run an AI model. The result depends on the chat model and information you provide.

## Full prompt

See [`prompt.md`](prompt.md).
