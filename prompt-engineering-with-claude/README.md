# Prompt Engineering with Claude (Anthropic)

A comprehensive, hands-on repository demonstrating **production-grade prompt engineering techniques** using Anthropic’s Claude models.

This project is based on the official **Anthropic Prompt Engineering Interactive Tutorial**, extended with my own structured summaries, explanations, and completed exercises.  
It focuses on building **reliable, controllable, and hallucination-resistant prompts** suitable for real-world AI systems.

---

## 🎯 Objectives

After completing this repository, you will understand how to:

- Design **clear, deterministic prompts** for LLMs
- Control model behavior using **roles, constraints, and formatting**
- Separate **instructions from data** using XML-style tagging
- Reduce hallucinations with **evidence-first prompting**
- Use **few-shot prompting** for consistency and format control
- Build **complex, multi-step prompts** for legal, financial, and coding assistants
- Create prompts suitable for **APIs, production systems, and AI agents**

---

## 📚 Course Structure & Covered Topics

### Beginner
1. **Basic Prompt Structure**
   - User / Assistant role separation
   - Message formatting rules
   - System vs User prompts

2. **Being Clear and Direct**
   - Explicit constraints
   - Output control
   - Avoiding ambiguity

3. **Assigning Roles**
   - Role-based prompting
   - Behavioral control
   - Style and reasoning lenses

---

### Intermediate
4. **Separating Data from Instructions**
   - Prompt templates
   - Variables (`{{INPUT}}`)
   - XML tags for strict boundaries

5. **Formatting Output & Speaking for Claude**
   - XML-tagged outputs
   - JSON-safe prompts
   - Assistant pre-filling for format control

6. **Precognition (Thinking Step-by-Step)**
   - Evidence → reasoning → decision pipelines
   - Order-sensitive prompting
   - Self-verification steps

7. **Few-Shot Prompting**
   - Example-driven behavior control
   - Formatting replication
   - Pattern consistency

---

### Advanced
8. **Avoiding Hallucinations**
   - Giving the model an “out” (“I don’t know”)
   - Evidence-first answering
   - NOT_FOUND fallbacks for document Q&A

9. **Complex Prompts for Industry Use Cases**
   - Legal research assistants
   - Financial chatbots
   - Coding review bots
   - Multi-input, multi-rule prompt architectures

---

## 🧠 Key Prompt Engineering Principles

- **Clarity beats cleverness**
- **Examples > instructions alone**
- **Structure reduces hallucinations**
- **Order matters**
- **Evidence before answers**
- **Production prompts must be deterministic**

---

## 📂 Repository Contents


prompt-engineering-with-claude/
│
├── README.md
├── anthropic_prompt_engineering.xlsx # Completed interactive exercises
├── lessons/
│ ├── lesson_01_basic_prompting.md
│ ├── lesson_02_clarity.md
│ ├── lesson_03_roles.md
│ ├── lesson_04_xml_tags.md
│ ├── lesson_05_output_formatting.md
│ ├── lesson_06_precognition.md
│ ├── lesson_07_few_shot.md
│ ├── lesson_08_hallucinations.md
│ └── lesson_09_complex_prompts.md
│
└── examples/
├── email_classification.md
├── legal_prompt.md
├── financial_chatbot.md
└── code_review_bot.md




---

## 🛠️ Tools & Concepts Used

- Anthropic Claude
- Prompt templates
- XML-style tagging
- Few-shot learning
- Evidence-based reasoning
- Deterministic output formatting

---

## 💼 Why This Matters for Recruiters

This repository demonstrates:

- **LLM literacy beyond basic prompting**
- Understanding of **production constraints**
- Ability to design **robust AI systems**
- Skills directly applicable to:
  - AI Agents
  - Chatbots
  - RAG pipelines
  - Enterprise LLM applications

---

## 📌 Author

**Dilrabo Khidirova**  
AI / ML Engineer  
Focus areas: Prompt Engineering, LLM Systems, Applied AI  

---

> This repository is intended for educational and professional demonstration purposes.

