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



Perfect — here’s your **final, exam-ready cheat sheet pack** for:

1. **Meta (HUD v. Meta)**
2. **VRS (Variance Reduction System)**
3. **Mobley v. Workday**

Everything is **clear, verbose, example-driven**, and **only based on what you studied**.

---

# 📘 **CHEAT SHEET 1 — HUD v. Meta (Algorithmic Housing Discrimination)**

---

# 🧠 **1. Core Idea**

> Meta’s advertising system **discriminates in housing ads** through how it:

* targets users
* expands audiences
* delivers ads
* prices ads

👉 Even when ads themselves are neutral.

---

# ⚙️ **2. How Meta’s System Works (2 Stages)**

---

## 🔹 Stage 1: Targeting (Eligible Audience)

👉 Advertiser selects:

* who SHOULD see the ad
* who should NOT

---

### 📌 Example:

* Exclude:

  * women
  * certain zip codes
  * “parents”

👉 Already risky

---

---

## 🔹 Stage 2: Delivery (Actual Audience) ⭐ MOST IMPORTANT

👉 Meta decides:

> who ACTUALLY sees the ad

---

### 📌 Example:

* Advertiser: “show to everyone”
* Meta:

  * shows 80% to men

👉 Discrimination happens HERE

---

## 🔥 Key Insight:

> Advertisers ≠ final control → **Meta controls outcomes**

---

# 🧩 **3. Lookalike / Special Ad Audience**

---

## 🔥 What it does:

* Takes a source group
* Finds “similar users”

---

### 📌 Example:

* Source = mostly white users
  → algorithm finds more white users

---

## 🧠 Why this is bad:

> Replicates and amplifies existing bias

---

# ⚙️ **4. Algorithmic Delivery Bias**

---

## 🔥 How it works:

Meta predicts:

> who is most likely to engage

---

### 📌 Example:

* Men click more on housing ads
  → system shows more ads to men

---

## 🧠 Meaning:

> Optimization → discrimination

---

# 💰 **5. Pricing Mechanism (VERY IMPORTANT)**

---

## 🔥 Idea:

> Some users are “cheaper” to show ads to

---

### 📌 Example:

* Ads cost less for men
  → system shows more ads to men

---

## 🧠 Insight:

> Pricing indirectly drives discrimination

---

# 🔁 **6. Proxy Discrimination**

---

## 🔥 Key idea:

> System uses proxies instead of explicit race/gender

---

### 📌 Examples:

* College → race
* Zip code → race
* Interests → gender

---

## 🧠 Meaning:

> Even without explicit targeting → same result

---

# ⚖️ **7. Theories of Discrimination (EXAM CRITICAL)**

---

## ✅ Disparate Treatment

> Uses protected traits directly

📌 Example:

* Algorithm uses gender

---

## ✅ Disparate Impact

> Neutral system → unequal outcomes

📌 Example:

* Women see fewer housing ads

---

## 🎯 FINAL ANSWER:

> Meta case = **BOTH**

---

# ⚠️ **8. MOST IMPORTANT INSIGHT**

> Even if advertiser is fair →
> system can still discriminate

---

# 🧠 **ONE-LINE SUMMARY**

> Meta’s system discriminates through targeting, lookalike expansion, delivery, and pricing, leading to both disparate treatment and disparate impact.

---

---

# 📘 **CHEAT SHEET 2 — VRS (Variance Reduction System)**

---

# 🧠 **1. What is VRS?**

> A system designed to **reduce differences (variance)** between:

* intended audience
* actual audience

---

# 🎯 **2. What it is built to do**

> Ensure:
> **who sees the ad ≈ who was targeted**

---

### 📌 Example:

* Target:

  * 50% men, 50% women

* Without VRS:

  * 80% men

* With VRS:

  * closer to 50/50

---

# ⚙️ **3. How it works**

---

## Step 1: Measure

* Who actually saw the ad

---

## Step 2: Compare

* Compare to intended audience

---

## Step 3: Adjust

* Rebalance delivery

---

### 📌 Example:

* Too many men
  → boost delivery to women

---

# 🔍 **4. Does VRS use demographics? (VERY TESTABLE)**

---

## ❌ NO:

> Individual-level demographics

---

## ✅ YES:

> Aggregated estimates

---

### 📌 Example:

* NOT:

  * “this user is Black”

* BUT:

  * “this group ≈ 40% Black”

---

## 🎯 FINAL ANSWER:

> Uses aggregated, not individual-level demographic data

---

# ⚠️ **5. Limitation**

> Only fixes **delivery bias**, not targeting

---

# 🧠 **ONE-LINE SUMMARY**

> VRS reduces disparities in ad delivery by aligning actual audiences with intended audiences using aggregated demographic estimates.

---

---

# 📘 **CHEAT SHEET 3 — Mobley v. Workday**

---

# 🧠 **1. Core Idea**

> AI hiring system repeatedly rejected a candidate → alleged bias

---

# ⚙️ **2. What Workday does**

* AI screening tool
* Evaluates applicants
* Can:

  * reject automatically

---

### 📌 Example:

* Apply → instant rejection → no human review

---

# ⚠️ **3. Where bias comes from**

---

## 🔥 Key idea:

> System infers protected traits indirectly

---

### 📌 Examples:

* College → race
* Graduation year → age
* Personality test → disability

---

# ⚖️ **4. Legal breakthrough**

---

## 🔥 Key ruling:

> Workday can be treated as an **agent of employers**

---

## 🧠 Meaning:

* Employers delegated hiring
* AI made decisions

---

# 🔥 **5. Theory of discrimination (EXAM QUESTION)**

---

## ✅ Disparate Impact

---

## 🧠 Why:

> No need to prove intent
> Only need unequal outcomes

---

### 📌 Example:

* Older candidates rejected more
* Black candidates rejected more

---

## 🎯 FINAL ANSWER:

> Mobley v. Workday = **Disparate Impact**

---

# ⚠️ **6. Important nuance**

> Not all AI tools are liable
> 👉 Only those that:

* directly influence decisions

---

# 🧠 **ONE-LINE SUMMARY**

> Workday’s AI hiring system is challenged under a disparate impact theory because it may disproportionately reject protected groups without intentional discrimination.

---

# 🚀 **FINAL 10-SECOND REVISION**

---

## 🧠 Meta:

> BOTH treatment + impact

---

## 🧠 VRS:

> Reduces delivery bias
> ❌ no individual demographics
> ✅ aggregated only

---

## 🧠 Workday:

> Disparate impact

---

---

If you want, I can now:
✅ give you **MCQs exactly like your quiz**
✅ or do a **rapid-fire test** to lock this in

Just say 👍


