# 📝 Reporting

> **Purpose**: Teach you how to craft HackerOne reports that triage teams immediately understand, trust, and prioritize for payout.  
> Reporting is the skill that converts research into real-world value.

---

## 1. What Reporting *Really* Means in Real Bug Bounties

Reporting is **not**:
- Dumping a PoC or tool output
- Writing “look, this is broken”  
- Following a template blindly

Reporting is **the art of translating your mental model of the system into a clear, actionable, and credible narrative**:

- Show **what the bug is**
- Show **why it matters**
- Show **how it can be reproduced safely**
- Show **what the impact is on the business or users**

A technically valid bug can be ignored if your report **fails to communicate impact**.

---

## 2. Why Reporting Matters on HackerOne

HackerOne triage teams:
- Process **hundreds of submissions per program**
- Prioritize reports with:
  - Clear severity justification
  - Reproducible steps
  - Business or user impact explanation

Poor reporting results in:
- Rejections
- Low payouts
- “Informative / N/A” responses

Effective reporting results in:
- Faster triage acceptance
- Higher payouts
- Triage confidence in your credibility

---

### 🎯 Key Elements Triage Cares About

1. **Clear Title**
   - Concise, specific, descriptive
   - Avoid generic titles like “Bug in login”

2. **Impact Explanation**
   - What breaks, who is affected, and how severe
   - Explain in business or user context

3. **Reproduction Steps**
   - Step-by-step, minimal assumptions
   - Include screenshots or logs if necessary, but not spam

4. **Technical Details**
   - Only enough for triage to validate
   - Show the logic, not just the payload

5. **Severity Assessment**
   - Suggest a reasoned severity
   - Link it to potential abuse or real-world consequences

---

## 3. How Experienced Hunters Approach Reporting

1. **Write After Analysis**
   - Never report before fully understanding the bug
   - Include system assumptions and trust boundaries if relevant

2. **Frame for the Triage Mindset**
   - Triagers are **risk managers**, not exploit enthusiasts
   - Highlight impact clearly, avoid technical jargon overload

3. **Provide Minimal, Reproducible Evidence**
   - Screenshots, curl commands, or steps
   - Avoid full scripts or sensitive payloads

4. **Anticipate Questions**
   - Include context that answers “Why does this matter?” and “How likely is this to be abused?”

5. **Maintain Professional Tone**
   - Avoid hype or dramatization
   - Stick to facts, analysis, and evidence

---

## 4. Common Beginner Mistakes & False Assumptions

### ❌ Mistake 1: Technical Dump
- Large logs or raw tool outputs overwhelm triage
- Hunters forget triage wants **signal, not noise**

### ❌ Mistake 2: No Business Context
- Explaining the technical bug only without explaining its **impact** is a frequent rejection cause

### ❌ Mistake 3: Overestimating Severity
- Inflated claims reduce credibility
- Triage will downgrade or reject

### ❌ Mistake 4: Reproducibility Assumptions
- Steps that require hidden knowledge or complex setup often fail
- Reports must be repeatable by a reasonably skilled triage engineer

---

## 5. Practical Checklist / Mental Model

### 🔍 Reporting Checklist
- [ ] Title is clear and descriptive
- [ ] Bug description explains **what** and **why**
- [ ] Reproduction steps are step-by-step and minimal
- [ ] Evidence is sufficient but concise
- [ ] Impact is explained in **business/user terms**
- [ ] Severity is reasoned, not inflated
- [ ] Optional mitigations suggested

### 🧠 Mental Model
> A report is **a story that convinces triage that your bug is real, impactful, and actionable**.  
> Think: “If I were triage, would I immediately understand this and trust it?”

---

## 6. Space for My Own Notes (MANDATORY)

### 🔒 Observations from Real Programs
-  
-  

### 🧠 Patterns I Keep Seeing
-  
-  

### ❗ Mistakes I Personally Made
-  
-  

### 🧪 Questions to Revisit Later
-  
-  

---

### Final Mentor Note

Great research is wasted if poorly reported.  
Master reporting, and your work **turns into payouts, credibility, and repeatable success**.  
This skill compounds across all programs and bug classes.
