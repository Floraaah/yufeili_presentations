---
title: '\[pre\]'
date: 2025-05-23
permalink: /posts/2025-05-23-1/
tags:
  - 
  - 
---

 {% include toc %}

# Information Design for Voluntary Disclosure

## A Theory of Participation-Optimal Coarsening

*Yufei Li* 

*Tsinghua University*

---

## <mark>Slide 1｜Outline</mark>

- 🌍 Motivation: Why carbon disclosure fails
- 🎯 Model Objective: Voluntary participation as a design goal
- 🧠 Structural Result: Finite partitions are optimal
- 📌 Extension: Signal + reward menus
- 🔄 Framing: From persuasion to participation

---

## <mark>Slide 2｜Motivation</mark>

🌍 **Voluntary carbon disclosure is the norm.**  
Platforms like CDP ask firms to submit carbon data *if they choose to participate*.

But reality contradicts transparency:

- ❌ High-emission firms opt out
- ❌ Stronger signals → lower participation
- ❌ Even “mandatory” regimes face symbolic compliance or avoidance

⚠️ **Disclosure paradox**:  

> The more informative the mechanism, the fewer firms disclose —  
> and the more biased the information becomes.

---

## <mark>Slide 3｜Problem Framing</mark>

🧠 **Planner's constraint**:  
No enforcement. Can only design the signal $\pi(s|\theta)$.

🎯 **Planner's goal**:  

> Maximize the mass of agents who **truthfully opt in** under IC/IR.

This is not persuasion or welfare maximization.

📌 **This changes the entire logic of information design.**

---

## <mark>Slide 4｜Main Contributions</mark>

🔑 **1. Finite Partition Optimality**  

> Even without message constraints, the optimal signal is a finite partition.  
> Coarsening improves participation — not a restriction, but an outcome.

🔑 **2. Menu Extension**  

> Allowing signal–reward menus (under budget),  
> we show that only **3 signal–reward cells** are needed for optimality.

📌 Both results show:  
**Simplicity emerges endogenously from the participation objective.**

---

## <mark>Slide 5｜Model Setup</mark>

📐 **Agent type**: $\theta \in [0,1]$ (pollution intensity)

🎛 **Planner's tool**: A signal structure $\pi(s|\theta)$

🧠 **Market**: Forms belief via posterior mean $\hat{\theta}_s$

💰 **Agent payoff**:

> Receives premium $g(\hat{\theta}_s)$, incurs cost $c(\theta)$

✅ **Opt-in condition**:

$$
g(\hat{\theta}_s) \ge c(\theta)
$$

🎯 Planner maximizes:  

> The measure of agents who **truthfully join** under the designed signal

---

## <mark>Slide 6｜Mechanism Design Tension</mark>

⚖️ **More precise signal** ⇒ more accurate belief  
❗ But: deters high-cost types from joining

💡 **Coarse signal**:

- Pools types
- Reduces exposure
- Increases participation

---

🔁 **Tradeoff**:  

> Transparency vs Inclusion

📌 This creates a *structural dilemma* —  
more information may lead to less participation.

---

## <mark>Slide 7｜Main Proposition</mark>

🔑 **Proposition (informal)**:  

> Even without restricting signal complexity,  
> the optimal mechanism is a **finite partition**.

✦ Planner pools types to enlarge the inclusion set

🪞 Simplicity emerges **from the structure**,  
not because of constraints or implementation limits

📌 This result explains why **real-world disclosures use ratings, bands, and tags**

---

## <mark>Slide 8｜Two Proof Paths</mark>

🛠️ **How do we prove finite partitions are optimal?**  
We use two independent approaches:

---

🧱 **1. Constructive Path**  

- Define participation threshold $\theta^*(s)$ via cutoff:  
  $g(\hat{\theta}_s) = c(\theta)$  
- Build blocks of types using increasing cutoffs  
- Show that refinement beyond a point reduces total inclusion

📌 Delivers **explicit partition structure**

---

📐 **2. Convex Analytic Path**  

- View planner's problem as optimization over posteriors
- Use:
  - **Weierstrass** ⇒ Existence
  - **Krein–Milman** ⇒ Extreme-point representation
  - **Carathéodory** ⇒ $\le 2$ posteriors suffice in $\mathbb{R}^1$

📌 Finite support implies finite partition — purely from convex geometry

---

✅ Both paths confirm:  

> **Finite partitions suffice**, under different assumptions

---

## <mark>Slide 9｜Reward Menu Extension</mark>

💡 What if planner can also assign **rewards** to each signal?

Now, each menu item is a pair $(\hat{\theta}_k, r_k)$, subject to budget:

$$
\sum \mu_k r_k \le B
$$

---

🔑 **Result**:  

> Only **3 signal–reward pairs** are needed for optimality

Two arguments again:

- 📐 **Convex Path**:  
  Carathéodory in $\mathbb{R}^2$ ⇒ $\le 3$ points

- 🧱 **Constructive Path**:  
  Marginal gain from new reward tiers drops after 3 blocks

---

📌 Real-world mechanisms (e.g., ESG incentives, rating–rebate menus) often use 3–5 categories  
→ This result matches institutional design practice

---

## <mark>Slide 10｜Back to the Carbon Disclosure</mark>

🔄 **Why this matters**:  
We've been discussing **mechanism design**,  
but it's grounded in a very real issue: **voluntary carbon disclosure**.

The **planner's problem** is not just about signal precision,  
but about **how to engage firms that need regulation the most**.

---

💡 Real-world dilemma:  
**More information ≠ better participation**  
Rather, **coarse signals** might be what incentivize participation.

- **Ratings, tags, and score bands**  
  **work because they lower exposure and increase opt-in mass**.

---

📌 This is why:

- **Policy design isn’t just about revealing the truth** —  
- **it’s about getting participants to engage.**

By showing how participation drives signal design,  
our model explains why **simple structures work best**.

---

## <mark>Slide 11｜Key Structural Insights</mark>

✅ **1. Voluntary inclusion needs structure, not just incentives**  
You can't simply subsidize participation —  
you must design signals that make agents *want to enter*

---

✅ **2. Simplicity emerges from the participation objective**  
Finite partitions and 3-cell menus arise not from constraint,  
but as the optimal solution to a non-concave objective

---

✅ **3. The key tension is robust**  
Whether using only signals or menus,  
the same tradeoff shapes the mechanism:

> 🌫️ Blur to include, 🎯 not to conceal

📌 This is why so many real-world mechanisms use ratings, tiers, and labels

---

## <mark>Slide 12｜Closing & Invitation</mark>

🙌 Thank you for listening!

This presentation focused on the **structural logic** behind  
voluntary disclosure and participation-optimal design

---

💬 I welcome any feedback on:

- The formulation of the objective and its motivation
- The realism of signal + reward extensions
- Further directions — e.g., heterogeneity, multi-dimensional types

🧠 Final question to leave you with:

> If full transparency deters participation,  
> what is the planner really optimizing for?
