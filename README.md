Perfect — here’s a **high-quality, exam-ready cheat sheet** for *this paper only* (Datta et al. + legal analysis).
I’ve made it **detailed, structured, and example-driven** so you can revise quickly and also answer deep questions.

---

# 📘 **CHEAT SHEET — Discrimination in Online Advertising (Datta et al.)**

---

# 🧠 1. CORE IDEA OF THE PAPER

> Online advertising systems can produce **discriminatory outcomes**, even when:

* ads are neutral
* advertisers don’t explicitly discriminate

---

## 🔥 Key insight:

> Discrimination can arise from the **entire ecosystem**, not just one actor.

---

# 🧪 2. BLACK-BOX AUDIT (FOUNDATION)

## ✅ Definition

> A **black-box audit** tests a system by controlling inputs and observing outputs without knowing how the system works internally.

---

## 🧪 What they did:

* Created **1000 simulated users**
* Same behavior:

  * same browsing
  * same job-search signals
* Only difference:

  * gender (male vs female)

---

## 🔥 Result:

> Ads shown differed significantly by gender

---

## 📊 Example (IMPORTANT):

* High-paying executive ads:

  * Men: **1852 times**
  * Women: **318 times**

---

## 🧠 Conclusion:

> Gender **causally affects** ad delivery

---

## ❗ Why causal?

* Randomized experiment
* p-value < 0.00005

---

## ✅ Exam line:

> The study establishes a causal relationship between gender and ad delivery.

---

# ⚠️ 3. BLACK-BOX LIMITATION

> You can detect discrimination, but **cannot explain why**

---

## Possible causes:

* Advertiser choices
* Platform algorithm
* User behavior
* Auction dynamics

---

## ✅ Exam line:

> The black-box nature prevents attribution of responsibility.

---

# 🧩 4. TYPES OF DISCRIMINATION

---

## 🔹 4.1 Direct discrimination

### Definition:

Explicit targeting using protected attributes

### Example:

* Advertiser sets:

  * “show job ads only to men”

---

## 🔹 4.2 Proxy discrimination

### Definition:

Using variables correlated with protected attributes

---

### Example:

* Target:

  * football fans
  * high-income executives

👉 These skew male → indirect discrimination

---

## 🔹 4.3 Masking (VERY IMPORTANT)

### Definition:

> Using neutral-looking attributes to hide discriminatory intent

---

### Example:

* Target:

  * age > 45
  * high salary
  * executive role

👉 Appears neutral
👉 Actually excludes women

---

## 🔥 Key idea:

> Discrimination can be hidden behind “legitimate” features

---

# ⚙️ 5. SOURCES OF DISCRIMINATION (WHO CAUSED IT)

---

## 🔹 5.1 Google (platform)

### Example:

* Algorithm decides:

  * men click more → show more ads to men

👉 Platform-driven bias

---

## 🔹 5.2 Advertiser

### Example:

* Explicit targeting:

  * men only

* OR proxy targeting:

  * executive-level professionals

---

## 🔹 5.3 Other advertisers (auction effect)

### Example:

* Other companies bid more for women
  → your ad goes mostly to men

---

## 🔹 5.4 Users (feedback loops)

### Example:

* Women click less on executive jobs
  → system learns this
  → shows fewer such ads to women

---

## 🔹 5.5 Combination

👉 Most realistic scenario:

> All factors interact

---

# 🔁 6. FEEDBACK LOOP (CRITICAL)

---

## 🔥 Mechanism:

1. Society has inequality
2. Users behave accordingly
3. Algorithm learns patterns
4. Reinforces inequality

---

## 🧠 Example:

* Fewer women in executive roles
  → women click less
  → algorithm shows fewer ads
  → worsens inequality

---

## ✅ Exam line:

> Feedback loops encode existing societal bias into algorithmic decisions.

---

# 🎯 7. TARGETING VS CONTENT (VERY IMPORTANT)

---

## 🔥 Key idea:

> Discrimination is NOT just in ad content — it’s in **who sees the ad**

---

## Example:

* Ad text:

  * “High-paying job available” (neutral)

* But:

  * only shown to men

👉 Still discriminatory

---

## ✅ Exam line:

> Targeting decisions alone can indicate discriminatory preference.

---

# ⚖️ 8. LEGAL FRAMEWORK

---

# 🔹 8.1 Title VII (employment law)

## Rule:

> Cannot publish job ads indicating preference based on protected class

---

## Limitation:

* Applies only to:

  * employers
  * employment agencies

👉 Platforms like Google:
❌ Usually NOT covered

---

## 🔥 Insight:

> Title VII is too narrow for modern ad systems

---

# 🔹 8.2 Fair Housing Act (FHA)

## Rule:

> Broader — applies to housing ads

---

## Key idea:

> Covers **targeting**, not just content

---

## Example:

* Showing housing ads only to white users
  → illegal even if ad text is neutral

---

# 🔹 8.3 Strict liability (VERY IMPORTANT)

## Rule:

> Intent does NOT matter

---

## Example:

* Even if advertiser didn’t intend bias
  → still illegal if outcome is discriminatory

---

## ✅ Exam line:

> Discriminatory advertising operates under a strict liability standard.

---

# 🔹 8.4 Section 230 (platform protection)

---

## Rule:

> Platforms are NOT liable for third-party content

---

## BUT…

## 🔥 Lose immunity if:

> Platform **materially contributes** to discrimination

---

# 🧠 9. 4 KEY LEGAL SCENARIOS

---

## ✅ Scenario 1: Advertiser targets gender

* Platform = neutral tool
* ✔ Protected (Section 230)

---

## ❗ Scenario 2: Algorithm decides targeting

* Platform actively chooses
* ❌ NOT protected

---

## ⚠️ Scenario 3: Keyword suggestions

* Usually neutral
* ✔ Protected

---

## ⚠️ Scenario 4: Auction effects

* Platform still controls delivery
* ❌ May be liable

---

## 🔥 Master rule:

> If platform shapes who sees ads → potential liability

---

# 🧱 10. FINAL TAKEAWAYS (MUST REMEMBER)

---

## 🧠 1. Causal discrimination exists

* Gender alone affects ads

---

## 🧠 2. Multiple sources

* Advertiser + platform + users + auctions

---

## 🧠 3. Proxy & masking

* Discrimination can be indirect and hidden

---

## 🧠 4. Feedback loops

* Algorithms reinforce societal bias

---

## 🧠 5. Targeting matters

* Who sees ads = key legal issue

---

## 🧠 6. No intent required

* Strict liability applies

---

## 🧠 7. Section 230 is limited

* Platforms lose protection if they contribute

---

# 🧠 ONE-LINE MASTER SUMMARY

> Online ad systems can produce discriminatory outcomes through complex interactions between advertisers, algorithms, user behavior, and auctions, and legal liability depends on whether platforms actively contribute to these outcomes.

---

# ⏭️ Next (HIGHLY IMPORTANT FOR QUIZ)

If you’re ready, I’ll give you:

👉 **Meta case cheat sheet (with EXACT answers to likely quiz questions):**

* Disparate treatment vs impact
* What is VRS
* Does VRS use demographics
* Mobley vs Workday classification

Just say **“Meta”**


Got it — here’s a **clean, focused summary of ONLY this Meta DOJ document + settlement (no extra info, no jumping ahead).**

---

# 📘 **Meta (HUD vs Meta) — Summary Cheat Sheet**

---

# 🧠 **1. What the case is about**

The U.S. Department of Justice (DOJ), based on a HUD investigation, sued Meta for:

> **Discriminatory housing advertising in violation of the Fair Housing Act (FHA)**

---

## 🔥 Core allegation:

> Meta’s **ad targeting and delivery system** discriminated against users based on protected characteristics.

---

# ⚖️ **2. Law involved**

* **Fair Housing Act (FHA)**
* Protects against discrimination based on:

  * race
  * color
  * religion
  * sex
  * disability
  * familial status
  * national origin

---

# ⚙️ **3. Where discrimination occurred (3 key parts)**

---

## 🔹 1. Advertiser targeting

* Meta allowed advertisers to:

  * include/exclude users based on protected traits

👉 Example:

* Excluding certain racial groups from housing ads

---

## 🔹 2. Lookalike / Special Ad Audience tool

* Algorithm finds users who “look like” a selected group

👉 Problem:

* Replicates bias from original group

---

## 🔹 3. Ad delivery algorithm (MOST IMPORTANT)

* Decides who actually sees ads

👉 Key issue:

> Even with fair targeting, delivery was biased

---

## 🔥 Critical takeaway:

> Discrimination happened at **multiple stages of the system**

---

# 🚨 **4. Key finding from HUD**

> Meta’s system delivered housing ads differently across protected groups

---

## 🔥 Important nuance:

> This happened **even when advertisers tried to target broadly**

---

## 🧠 Meaning:

* Bias is not just advertiser-driven
* It is **algorithm-driven**

---

# ⚖️ **5. Theories of discrimination (EXAM CRITICAL)**

> The complaint alleges:

* **Disparate Treatment**
* **Disparate Impact**

---

## 🔹 Disparate Treatment

* Meta **intentionally used protected characteristics**
* Example: algorithms using race/gender

---

## 🔹 Disparate Impact

* Algorithms caused **unequal outcomes across groups**
* Example: some groups saw fewer housing ads

---

# 🔧 **6. What Meta was required to do (Settlement)**

---

## ❌ Remove tool

* Stop using **Special Ad Audience (Lookalike tool)**

---

## ⚙️ Build new system

* Must reduce disparities in ad delivery

---

## 🔍 Oversight

* Subject to:

  * DOJ approval
  * court oversight
  * independent reviewer

---

## ❌ Restrict targeting

* Cannot allow targeting based on protected traits

---

## 💰 Penalty

* Pay civil fine

---

# ⚠️ **7. If Meta fails**

* Settlement ends
* Case goes to court

---

# 🔥 **8. Key legal shift**

> Platforms (like Meta) can be held responsible for algorithmic discrimination

---

## 🧠 Meaning:

* Not just advertisers
* The **system itself is liable**

---

# 🎯 **9. Most important insights**

---

## 🧠 1.

> Discrimination can happen in **delivery**, not just targeting

---

## 🧠 2.

> Algorithms can use or replicate protected characteristics

---

## 🧠 3.

> Even neutral advertiser intent does NOT prevent discrimination

---

## 🧠 4.

> Lookalike systems amplify existing bias

---

## 🧠 5.

> Platforms are accountable under FHA

---

# 🧠 **ONE-LINE MASTER SUMMARY**

> Meta’s ad system was found to discriminate in housing ads through targeting, lookalike expansion, and delivery algorithms, leading to both disparate treatment and disparate impact, and the settlement requires major system-level changes and oversight.

---

# ⏭️ Next

When you’re ready, send the next doc — we’ll extract:

* VRS
* Mobley vs Workday
* Final quiz answers cleanly 🚀

