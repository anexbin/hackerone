# 📝 Program Analysis

> **Purpose**: Learn how to evaluate and prioritize HackerOne programs, scope, and targets before touching any tools.  
> Proper program analysis is the bridge between orientation and actual testing.

---

## 1. What Program Analysis *Really* Means in Real Bug Bounties

Program analysis is **not**:
- Reading the program description once
- Memorizing a list of assets
- Randomly opening endpoints

In real bounty hunting, program analysis means:
- Understanding **asset criticality** (which features actually matter to the business)
- Mapping **trust boundaries** between users, services, and APIs
- Identifying **implicit permissions or blind spots**
- Estimating **likelihood of payout** based on historical reports and program behavior

Key idea:
> Not all assets are equal. Not all bugs are equal. Your job is to focus where impact meets feasibility.

---

## 2. Why Program Analysis Matters on HackerOne

HackerOne rewards **impact and clarity**, not raw bug count.

### 🧪 Triage Perspective
- Triage teams see **hundreds of submissions per program**.
- Reports that demonstrate **understanding of the program** are **fast-tracked**.
- Reports without context often get:
  - Informative / N/A
  - Low payout or rejection

Proper program analysis ensures:
- You submit **high-signal findings**
- You avoid wasting time on **irrelevant endpoints**
- You can **justify your severity and impact**

---

### 🎯 Scope & Policy Interpretation
Program analysis is where you:
- Identify **in-scope vs out-of-scope assets**
- Spot **program-specific rules** (e.g., “do not brute-force login endpoints”)
- Detect **implicit business logic areas** that might be overlooked

Failing here often results in:
- Reports being rejected for “out of scope”
- Wasted hours on low-value bugs

---

### 💰 Payout Estimation
Analysis lets you:
- Prioritize high-value targets
- Avoid “fun but low-value” issues
- Predict which findings may earn **medium to high payouts**

---

## 3. How Experienced Hunters Analyze Programs

Experienced hunters approach analysis **like a strategist**:

1. **Asset Enumeration**
   - Map all exposed interfaces: web, mobile, API, admin portals
   - Identify critical assets: authentication, payment, data flows

2. **Historical Data Review**
   - Read disclosed reports (if public)
   - Note patterns: common bug classes, triage behavior

3. **Trust & Permission Mapping**
   - Who can do what in the system?
   - Identify escalation paths or cross-account interactions

4. **Logic & Flow Analysis**
   - Observe edge cases in workflows
   - Identify steps that fail silently or are under-validated

5. **Risk vs Effort Estimation**
   - Assess which targets are both exploitable **and impactful**
   - Avoid spending time on low-risk, low-impact endpoints

---

## 4. Common Beginner Mistakes & False Assumptions

### ❌ Mistake 1: Treating All Endpoints Equally
Not all URLs or APIs are equally valuable.
- Beginners test everything
- Experienced hunters focus on **high-leverage targets**

---

### ❌ Mistake 2: Ignoring Program History
- Beginners ignore disclosed reports
- Professionals use them to **predict triage behavior** and identify **weak points**

---

### ❌ Mistake 3: Confusing Technical Bugs With Business Impact
- A minor bug may be interesting but worthless to the program
- Analysis focuses on **real-world consequences**

---

### ❌ Mistake 4: Jumping Straight to Exploitation
- Beginners try exploits immediately
- Professionals map **flows, permissions, and logic** first

---

## 5. Practical Checklist / Mental Model

### 🔍 Analysis Checklist
- [ ] List all program assets and endpoints
- [ ] Identify critical systems (auth, payments, admin)
- [ ] Map user roles and permissions
- [ ] Check program rules and scope
- [ ] Review historical reports and disclosed patterns
- [ ] Identify potential high-impact logic paths
- [ ] Estimate effort vs payout

### 🧠 Mental Model
> Think of the program as a **small, dynamic ecosystem**.  
> Your goal: find **stress points and weak assumptions** before touching any inputs.

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

Program analysis is where you separate **random testers** from **high-level hunters**.  
Master this, and **your findings will consistently get attention, respect, and payouts**.
