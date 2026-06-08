# 🐍 Python Foundation — Backend & AI Engineering

This repository contains a structured, hands-on Python learning path focused on:

* backend engineering
* system design thinking
* AI engineering foundations

The goal is to learn Python as a **real engineering tool**, not just syntax.

---

# 📁 Project Structure

Each lesson is fully isolated and runnable.

```text
python-foundation-engineering/
│
├── lessons/
│   ├── 01_variables_and_types.py
│   ├── 02_functions.py
│   ├── 03_oop_basics.py
│   ├── 04_iterators_generators.py
│   ├── ...
│
├── playground.py
├── requirements.txt
├── .venv/   (NOT committed to git)
└── README.md
```

---

# 🧠 What is `playground.py`?

`playground.py` is your:

> 🔬 experimentation file (scratch space)

You use it when you want to:

* test ideas quickly
* try small experiments
* debug behavior
* combine multiple concepts temporarily

### Important rule:

* ❌ Do NOT treat it as a lesson file
* ❌ Do NOT build structured code inside it
* ✅ It is disposable experimentation space

Think of it like a “laboratory notebook”, not a textbook.

---

# 🐍 Virtual Environment Setup (IMPORTANT)

This repo uses a **Python virtual environment (`venv`)** to isolate dependencies.

---

## 🔧 Setup

### 1. Create virtual environment

```bash
python -m venv .venv
```

---

### 2. Activate environment

#### Linux / Mac

```bash
source .venv/bin/activate
```

#### Windows (PowerShell)

```bash
.venv\Scripts\activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Confirm you're inside venv

```bash
which python
```

You should see something like:

```text
.../python-foundation-engineering/.venv/bin/python
```

---

# ▶️ How to Run Lessons

Each lesson is independent.

Run like this:

```bash
python lessons/01_variables_and_types.py
```

Then move forward step by step:

```bash
python lessons/02_functions.py
python lessons/03_oop_basics.py
```

---

# 🔁 Learning Workflow (VERY IMPORTANT)

Each lesson follows this cycle:

### 1. Run it

Understand what it does.

### 2. Modify it

Break things, change values, experiment.

### 3. Extend it

Add your own small variation.

### 4. Move on

Do NOT over-optimize or expand lessons into projects.

---

# 🚦 Core Rule

> One file = one concept = one focused skill

Avoid:

* mixing topics in one file
* turning lessons into projects
* skipping execution

---

# 🎯 Purpose of This Repo

This repo builds the foundation for:

* backend engineering (FastAPI, APIs, databases)
* system design thinking
* AI engineering pipelines
* real-world problem solving

---

# 🧱 Outcome

By completing this, you should be able to:

* read and write clean Python confidently
* understand core language mechanics deeply
* think in systems instead of scripts
* prepare for backend + AI engineering roles
