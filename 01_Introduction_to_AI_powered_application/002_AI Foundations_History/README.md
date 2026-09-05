# 🤖 AI Foundations, History & Terminology

Short and simple notes covering the main concepts of Artificial Intelligence.

## 🧠 1. Intelligence

**Intelligence** = the ability to understand situations, learn from experience, connect ideas, solve problems, and achieve goals.

### Natural Intelligence

Intelligence found in humans and animals.

* Learning from experience
* Emotions
* Creativity
* Common sense
* Social understanding
* Flexible decision-making

### Artificial Intelligence

Machines that simulate intelligent behavior using:

* Data
* Algorithms
* Models
* Software & hardware
* Mathematical/statistical patterns

---

# 🕰️ 2. History of AI

### 1950 — Alan Turing

* Asked: **"Can machines think?"**
* Proposed the **Imitation Game / Turing Test**

### 1956 — Dartmouth Conference

* The term **Artificial Intelligence** was introduced.
* Early AI focused on **Symbolic AI** and manually written rules.

### Rule-Based AI

```text
IF condition
THEN action
```

Problem: real-world situations are too complex for humans to write every rule.

### AI Winters

Periods when AI research, funding, and excitement declined because AI failed to meet expectations.

### 2010s — Deep Learning Boom

Two major factors:

* **Big Data**
* **GPUs / Fast Hardware**

These enabled neural networks to learn complex patterns from large datasets.

### 2017 — Transformer Era

The paper **"Attention Is All You Need"** introduced the Transformer architecture.

Transformers improved how models understand relationships and context in text.

**GPT = Generative Pre-trained Transformer**

---

# 🪆 3. AI → ML → DL → Generative AI

```text
Artificial Intelligence (AI)
        ↓
Machine Learning (ML)
        ↓
Deep Learning (DL)
        ↓
Generative AI
```

### AI

The broadest concept: computers performing tasks that appear intelligent.

### Machine Learning

AI that learns patterns from **data** instead of having every rule manually programmed.

### Deep Learning

Machine Learning using **multi-layer neural networks**.

Used for:

* Images
* Speech
* Text
* Video
* Complex pattern recognition

### Generative AI

Deep Learning systems that **create new content**.

Examples:

* Text
* Images
* Audio
* Music
* Code

---

# 📦 4. AI Model

A **model** is the learned result of training.

```text
Data
 ↓
Training
 ↓
Model
 ↓
Inference
 ↓
Output
```

**Training** = learning patterns.

**Inference** = using the learned model on new input.

---

# 🎯 5. ANI, AGI & ASI

### ANI — Artificial Narrow Intelligence

AI specialized in specific tasks.

**Example:** navigation, facial recognition, game-playing systems, LLMs.

> ANI = Specialist

### AGI — Artificial General Intelligence

Hypothetical AI capable of performing a broad range of intellectual tasks at human level.

> AGI = Human-level general intelligence

### ASI — Artificial Superintelligence

Hypothetical AI that surpasses human intelligence.

> ASI = Beyond human intelligence

---

# 🏗️ 6. Foundation Models

Large general-purpose models trained on broad data.

They can be adapted using:

* Prompts
* Tools
* Retrieved data
* Fine-tuning

---

# 🧰 7. Types of AI Models

| Model                | Used For             |
| -------------------- | -------------------- |
| **LLM**              | Text & code          |
| **Vision Model**     | Images & video       |
| **Audio Model**      | Speech & sound       |
| **Multimodal Model** | Text + image + audio |

---

# 💬 8. LLM — Large Language Model

LLMs are **token predictors**.

They generate responses by repeatedly predicting the next likely token.

```text
Prompt
 ↓
Predict next token
 ↓
Add token
 ↓
Predict next token
 ↓
Repeat
 ↓
Response
```

LLMs generate based on learned patterns and the context provided.

---

# 🔤 9. Tokens

LLMs process text as **tokens**, not necessarily complete words.

A token can be:

* A word
* Part of a word
* Punctuation
* Other text pieces

Tokens affect:

* Cost
* Speed
* Context limits
* Input/output length

---

# 🧠 10. Context Window

The **context window** is the amount of information a model can consider during a request.

It can include:

* System instructions
* User messages
* Chat history
* Documents
* Retrieved information
* Examples
* Tool outputs

### Analogy

> Context window = a **whiteboard** containing the information the model can currently use.

---

# 🌡️ 11. Temperature

Temperature controls how predictable or creative the model's output is.

| Temperature | Behavior             | Good For                |
| ----------- | -------------------- | ----------------------- |
| **Low**     | Stable & predictable | Code, math, factual Q&A |
| **Medium**  | Balanced             | Chatbots, tutoring      |
| **High**    | Creative & varied    | Stories, brainstorming  |

---

# ⚠️ 12. Hallucinations

A **hallucination** occurs when AI produces an answer that sounds confident but is:

* Wrong
* Invented
* Unsupported

Example:

AI may invent a package, function, API, or technical fact that does not exist.

### Developer Rule

> **Never blindly trust AI output. Verify and test it.**

---

# 👨‍💻 13. AI in Everyday Life

Common examples:

* 🎬 Recommendation systems
* 📧 Spam filters
* 🗺️ Navigation
* 💻 Code assistants
* 💬 Customer support bots
* 🔎 Semantic search
* 👤 Face recognition
* 🎤 Voice assistants


---

# 🎯 Final Lesson

> **AI is a co-pilot, not the captain.**

Understand what AI produces, **test it, verify it, and take responsibility for the final application**.

The goal is not to memorize every term. The goal is to understand how **AI models become part of real software applications**.
