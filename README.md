Perfect — I’ll turn everything into a **clean, structured, exam-ready master document** (like a README you can revise from).
This will be **detailed, conceptual (no math)**, with **examples + mental models + connections**.

---

# 📄 MASTER NOTES

## Improving Fairness in Machine Learning Systems: What Do Industry Practitioners Need?

---

# 🧠 1. CORE IDEA OF THE PAPER

---

## 🔥 Central Thesis

> Fairness in ML is not just a modeling problem — it is a **real-world, system-level, socio-technical problem**.

---

## ❗ Key Problem

There is a **gap between research and practice**:

| Research (Academia)            | Industry (Practice)      |
| ------------------------------ | ------------------------ |
| Focus on models                | Focus on data            |
| Uses fairness metrics          | Lacks metrics/tools      |
| Assumes demographics available | Often unavailable        |
| Controlled settings            | Messy real-world systems |

---

## 🧠 Mental Model

```text
Research builds tools → based on theory
Industry faces problems → based on reality

→ Mismatch → fairness tools not useful in practice
```

---

# 🌍 2. WHY FAIRNESS MATTERS

---

## ML systems affect:

* Hiring decisions
* Healthcare
* Policing
* Search results
* Education

---

## ⚠️ Key Risk

> ML **amplifies existing bias**

---

### 💡 Example

* Biased hiring data → model → rejects certain groups more
* Search engine → shows stereotypes

---

## 🧠 Key Insight

➡️ *ML doesn’t just reflect bias — it scales it*

---

# 🔬 3. WHAT THE AUTHORS DID (METHODS)

---

## Two-part study:

### 1. Interviews (deep understanding)

* 35 practitioners
* across 25 teams, 10 companies

---

### 2. Survey (validation)

* 267 practitioners

---

## 🧠 Why both?

| Method     | Purpose           |
| ---------- | ----------------- |
| Interviews | discover problems |
| Survey     | confirm problems  |

---

## 🔥 Important Concepts

---

### ✔️ “Fairness definition left open”

* They didn’t define fairness strictly
* Wanted practitioners’ interpretation

👉 Insight:
➡️ *Fairness is subjective and context-dependent*

---

### ✔️ “Oracle question”

> “If you had a magical oracle, what would you ask?”

👉 Purpose:

* reveal **true unmet needs**

---

### ✔️ Studied full ML pipeline

* data collection
* modeling
* deployment
* evaluation

👉 Insight:
➡️ *Fairness is not just about the model*

---

# 🔥 4. KEY THEMES (MOST IMPORTANT)

---

# 🧩 THEME 1: Fairness-aware Data Collection

---

## 🔥 Core Idea

> Data is the **primary source of bias**

---

## ❗ Key Contrast

| Research  | Practice |
| --------- | -------- |
| Fix model | Fix data |

---

## 📊 Evidence

* 73% → main fix = **collect more data**

---

## 🚨 Problems

### 1. “Wild west” data collection

* no structured process
* teams ingest whatever is available

👉 Example:

> “If data exists, we use it”

---

### 2. Poor communication

* data collectors ≠ model developers

---

### 3. Lack of targeted data collection

* teams don’t know:

  * *what data is missing*

---

## 💡 Example

Essay scoring:

* very few high-scoring African American students
  → model becomes unfair

---

## 🔥 Test Sets (VERY IMPORTANT)

---

### Purpose:

* detect fairness issues

---

### Example:

* Image model labels:

  * female doctor → “nurse”

---

### Solution:

* design test sets with:

  * diverse subgroups

---

## 🧠 Key Takeaways

* Data quality drives fairness
* Need targeted data collection
* Test sets must be fairness-aware

---

# 🧩 THEME 2: Blind Spots

---

## 🔥 Core Idea

> Teams don’t know what they don’t know

---

## ❗ Problem: Unknown unknowns

---

### Example:

* Team considers:

  * race, gender

BUT misses:

* language (native vs non-native)

---

## 🔥 Key Insight

➡️ *Fairness groups depend on context*

---

## 🚨 Reactive detection

---

### Reality:

> Bias is discovered only after:

* user complaints
* media backlash

---

### Quote idea:

“You’ll know when someone raises hell online”

---

## 📊 Evidence

* 51% discover issues **after deployment**

---

## 🚨 Knowledge limitation

---

### Problem:

* No team knows all biases

---

### Example:

* Model fails on Taiwanese celebrities
* Team doesn’t know what they look like

---

## 🧠 Key Takeaways

* Blind spots = biggest barrier
* Fairness detection is reactive
* Cultural/domain knowledge matters
* Need knowledge sharing

---

# 🧩 THEME 3: Proactive Auditing

---

## 🔥 Core Idea

> Fairness auditing is currently **reactive, manual, and weak**

---

## 🚨 Problems

---

### 1. No fairness metrics

* unlike accuracy

👉 Insight:
➡️ “You can’t fix what you can’t measure”

---

### 2. Lack of demographics

* race/gender often unavailable

---

### 3. Proxy methods flawed

* infer race from name/location
  → introduces new bias

---

### 4. Scalability issue

* small user studies
* not representative

---

### 5. Systemic vs one-off

* hard to tell:

  * isolated bug
  * widespread issue

---

## 🧠 Key Takeaways

* Auditing is not systematic
* Metrics are missing
* Privacy vs fairness tradeoff
* Need scalable tools

---

# 🧩 THEME 4: System-Level Fairness

---

## 🔥 Core Idea

> Fairness is a property of the **entire system**, not just the model

---

## 🚨 Problem with research

* focuses on:

  * simple tasks
* ignores:

  * real-world complexity

---

## 💡 Example

Search query: “CEO”

* results: mostly white men

---

### Fix attempt:

* diversify results

---

### User reaction:

* “This is manipulation”

---

## 🧠 Key Insight

➡️ *Fairness depends on user perception*

---

## 🔥 Complex systems

* chatbots
* search engines
* tutoring systems

---

👉 involve:

* interactions
* feedback loops

---

## 🔥 Solution: Simulation

---

### Examples:

* simulate conversations
* simulate users

---

## 🧠 Key Takeaways

* Model metrics ≠ real fairness
* User perception matters
* Need system-level evaluation
* Simulation is key

---

# 🧩 THEME 5: Fixing Fairness Issues

---

## 🔥 Core Idea

> Fixing bias is **hard and uncertain**

---

## 🚨 Problems

---

### 1. Which strategy to use?

Options:

* more data
* change model
* redesign system

---

### 2. Trade-offs

Fixing fairness may:

* hurt accuracy
* harm UX

---

### 💡 Example

Fix improves metrics
→ users feel worse experience

---

### 3. Side effects

* fixing one bias → creates another

---

### 4. No guidance on data

* “how much data is enough?”

---

### 5. Ethical dilemmas

---

#### Example:

* Should we:

  * change society via models?
  * target specific groups for data?

---

## 🔥 System redesign

---

### Example:

* Replace:

  * “doctor/nurse” → “healthcare professional”

---

👉 reduces harm without fixing model

---

## 🧠 Key Takeaways

* No clear fix strategy
* Trade-offs everywhere
* Ethical decisions involved
* System design matters

---

# 🧩 THEME 6: Human Bias

---

## 🔥 Core Idea

> Humans in the pipeline introduce bias

---

## 📍 Where?

* data labeling
* scoring
* evaluation

---

## 💡 Example

Essay grading:

* different writing style → different score

---

## 🔥 Solution: Counterfactual testing

---

### Idea:

* same content
* different style

👉 check if outcome changes

---

## 🧠 Key Takeaways

* Human bias propagates into ML
* Need tools to audit humans
* Counterfactuals are powerful

---

# 🧠 5. FINAL BIG IDEAS (MOST IMPORTANT)

---

## 🔥 1. Data > Model

* bias mainly comes from data

---

## 🔥 2. Fairness is system-level

* includes:

  * model
  * UI
  * humans

---

## 🔥 3. Blind spots are critical

* biggest barrier = unknown bias

---

## 🔥 4. Lack of infrastructure

* no tools
* no metrics
* no processes

---

## 🔥 5. Fairness is socio-technical

---

### Meaning:

You need:

* technical solutions
* organizational change
* policies
* education

---

# 🎯 FINAL EXAM CHEAT SHEET

---

### If you remember ONLY this:

---

* ML amplifies bias
* Research ≠ practice
* Data is the main issue
* Blind spots = unknown bias
* Auditing is reactive
* No fairness metrics in practice
* Demographics often unavailable
* Fairness is system-level
* Fixing bias has trade-offs
* Humans introduce bias

---

---

# 🚀 If you want next step

I can:

* give you **MCQs + answers**
* give **case-based questions (very likely in exam)**
* or connect this to your **fairness metrics (DP, EO, calibration)**

Just tell me 👍
