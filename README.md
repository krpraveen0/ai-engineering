# AI Engineering with Python 🚀

**A complete, industry-grade AI Engineering curriculum** that takes you from Python & AI fundamentals to **LLMs, Agentic AI, and production-ready systems**.

This repository is designed to be used by:

* Software engineers transitioning into AI
* ML / LLM / Agentic AI engineers
* Universities & training institutes
* Corporate upskilling programs

> ⚠️ This is **not a tutorial repo**. It is a **structured curriculum repository** with controlled progression and production-quality practices.

---

## 🧭 How This Repository Is Organized

The course is divided into **modules (weeks)**. Each week focuses on one coherent theme and builds on previous weeks.

### 📁 Directory Structure (Main Branch)

```
ai-engineering-with-python/
├── CURRICULUM_MAP.md
├── README.md
├── week-01/
│   ├── starter/
│   └── solution/
├── week-02/
│   ├── starter/
│   └── solution/
...
├── week-24/
│   ├── starter/
│   └── solution/
├── datasets/
├── instructor-notes/
└── requirements.txt
```

* **starter/** → notebooks with TODOs for learners
* **solution/** → reference implementations (for instructors / self-review)

---

## 🌿 Branch Strategy (IMPORTANT)

This repository uses **branches to guide learning progression** and control access to content.

### 🔑 Branches

| Branch                           | Purpose                                  |
| -------------------------------- | ---------------------------------------- |
| `main`                           | Curriculum structure + placeholders only |
| `weeks-01-04`                    | Foundations & ML (Weeks 1–4)             |
| `weeks-05-08`                    | Deep Learning, NLP, LLMs, RAG            |
| `weeks-09-12`                    | Agentic AI & Production                  |
| `weeks-13-24`                    | Advanced systems & capstone              |
| `solutions-private` *(optional)* | Instructor-only solutions                |

> Learners should **start from `main`** and switch branches gradually.

---

## 🚀 How to Use This Repository (Step-by-Step)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/krpraveen0/ai-engineering-with-python.git
cd ai-engineering-with-python
```

---

### 2️⃣ Start From the `main` Branch

```bash
git checkout master
```

Use this branch to:

* Understand the **full curriculum map**
* See week-by-week structure
* Read instructions before coding

---

### 3️⃣ Switch to Learning Branches (Recommended Flow)

#### Weeks 1–4 (Foundations & ML)

```bash
git checkout weeks-01-04
```

#### Weeks 5–8 (DL, NLP, LLMs, RAG)

```bash
git checkout weeks-05-08
```

#### Weeks 9–12 (Agentic AI & Production)

```bash
git checkout weeks-09-12
```

#### Weeks 13–24 (Advanced & Capstone)

```bash
git checkout weeks-13-24
```

---

## 📓 How to Work With Notebooks

### For Learners

1. Open notebooks from the **starter/** folder
2. Follow markdown explanations
3. Complete all `TODO` sections
4. Run cells incrementally
5. Compare with solutions only after completion

> ⚠️ Do **not** jump ahead. Each week depends on the previous one.

---

### For Instructors / Self-Learners

* Use **solution/** notebooks as reference
* Optionally keep solutions in a private branch
* Use PRs to review student submissions

---

## 🧪 Environment Setup

### Python Version

```
Python 3.10+
```

### Install Dependencies

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 📘 Curriculum Contract

Before adding or generating any content:

* Read **`CURRICULUM_MAP.md`**
* Follow it as the **single source of truth**

Copilot and contributors **must not**:

* Invent topics
* Skip weeks
* Mix difficulty levels

---

## 👥 Contribution Guidelines

* Each PR should target **one batch of weeks**
* Keep PRs small and reviewable
* Maintain naming conventions
* Respect starter vs solution separation

---

## 🎓 Who This Repository Is For

* Engineers preparing for **AI / ML / LLM roles**
* Companies building internal AI training
* Educators teaching modern AI engineering

---

## 📜 License

MIT License — free to learn, fork, and build upon.

---

## 🧠 Final Note

This repository is designed to teach **how real AI systems are built**, not just how models are trained.

> Treat this like an **AI Engineering textbook implemented in code**.