# AI Foundations, History & Terminology

Short notes on the fundamentals, history, and terminology of Artificial Intelligence.

## 1. Intelligence

**Intelligence** is the ability to learn, understand, solve problems, make decisions, and achieve goals.

* **Natural Intelligence:** Human and animal intelligence.
* **Artificial Intelligence:** Machines performing tasks that normally require intelligence using data, algorithms, and models.

## 2. History of AI

* **1950 — Alan Turing:** Asked, "Can machines think?" and proposed the Turing Test.
* **1956 — Dartmouth Conference:** AI became an established field; early systems used symbolic rules.
* **AI Winters:** Periods when AI progress and funding declined because expectations were not met.
* **2010s — Deep Learning:** Big Data and GPUs enabled major progress in neural networks.
* **2017 — Transformers:** "Attention Is All You Need" introduced the Transformer architecture, which became important for modern language models.
* **GPT:** Generative Pre-trained Transformer.

## 3. AI → ML → DL → Generative AI

```text
AI
 ↓
Machine Learning
 ↓
Deep Learning
 ↓
Generative AI
```

* **AI:** Broad field of intelligent computer systems.
* **ML:** Systems that learn patterns from data.
* **DL:** ML using multi-layer neural networks.
* **Generative AI:** Models that generate text, images, audio, video, or code.

## 4. Model, Training & Inference

```text
Data → Training → Model → Inference → Output
```

* **Training:** Learning patterns from data.
* **Model:** The learned representation produced by training.
* **Inference:** Using the model to produce results from new input.

## 5. ANI, AGI & ASI

* **ANI:** AI designed for specific tasks.
* **AGI:** Hypothetical AI capable of general human-level intellectual tasks.
* **ASI:** Hypothetical AI that surpasses human intelligence.

```text
ANI → Specialist
AGI → General intelligence
ASI → Beyond human intelligence
```

## 6. Foundation Models

Large general-purpose models trained on broad datasets.

They can be adapted through:

* Prompts
* Tools
* Retrieved information
* Fine-tuning

## 7. Common AI Models

| Model            | Main Use                  |
| ---------------- | ------------------------- |
| LLM              | Text and code             |
| Vision Model     | Images and video          |
| Audio Model      | Speech and sound          |
| Multimodal Model | Text, images, audio, etc. |

## 8. LLM — Large Language Model

LLMs generate text by repeatedly predicting the next likely **token** based on the available context.

```text
Prompt
 ↓
Predict token
 ↓
Add token
 ↓
Repeat
 ↓
Response
```

## 9. Tokens

Tokens are the pieces of text processed by an LLM.

A token can be:

* A word
* Part of a word
* Punctuation
* Other text pieces

Tokens affect context size, cost, speed, and response length.

## 10. Context Window

The **context window** is the information a model can consider during a request.

It may include:

* Instructions
* User messages
* Chat history
* Documents
* Retrieved information
* Tool results

**Simple idea:** Context window = the model's working information.

## 11. Temperature

Temperature controls the randomness of model output.

| Temperature | Behavior         | Example          |
| ----------- | ---------------- | ---------------- |
| Low         | More predictable | Code, facts      |
| Medium      | Balanced         | Chat, tutoring   |
| High        | More varied      | Creative writing |

## 12. Hallucinations

A **hallucination** happens when AI produces information that sounds correct but is actually wrong or invented.

Examples:

* Fake APIs
* Non-existent packages
* Incorrect technical information

**Developer rule:**

> Never blindly trust AI output. Verify and test it.

## 13. AI in Everyday Software

AI is used in:

* Recommendation systems
* Spam filters
* Navigation
* Code assistants
* Customer support
* Semantic search
* Face recognition
* Voice assistants

## Final Lesson

> **AI is a co-pilot, not the captain.**

Use AI to work faster, but **understand, verify, test, and take responsibility for the final result**.

The goal is not to memorize every AI term. The goal is to understand how AI models become part of real software applications.
