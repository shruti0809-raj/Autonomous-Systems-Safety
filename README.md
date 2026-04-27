# Autonomous Systems Safety  
### Ethical Decision-Making in Self-Driving Systems

Autonomous systems are increasingly being deployed in environments where decisions can have direct consequences on human life. In such settings, decision-making is not purely technical it reflects underlying ethical frameworks, trade-offs, and assumptions about how harm should be distributed.

This project explores how different moral decision-making models behave in high-stakes autonomous driving scenarios, and how these behaviors change when systems interact with each other.

---

## Overview

Using simulated self-driving scenarios, this work analyzes three distinct ethical frameworks:

- **Humanist** — minimizes total harm  
- **Protectionist** — prioritizes the safety of the vehicle’s occupants  
- **Profit-based** — minimizes financial or liability cost  

The analysis focuses not only on individual decisions, but on how these frameworks behave in **multi-agent environments**, where multiple autonomous systems interact simultaneously.

---

## Key Questions

- Should autonomous systems prioritize passengers or minimize overall harm?  
- What happens when multiple systems follow the same ethical rule?  
- Can ethical decision-making vary across countries or contexts?  
- Do traffic rules align with ethical outcomes in edge-case scenarios?  

---

## Scenario Walkthrough

The following visuals illustrate how different ethical frameworks process the same scenario and arrive at different decisions.

---

### 1. Scenario Setup

#### Selecting Ethical Framework
[Choosing Principle](./images/choosing principle.png)

#### Selecting Scenario (School Bus Case)
[Select Scenario](./images/select scenario.png)

---

### 2. Humanist Model (Minimize Total Harm)

#### Scenario Execution
[Humanist Approach](./images/humanist 1.png)

#### Profiling and Impact Analysis
[Humanist Profiling](./images/humanist 2.png)

#### Final Decision Summary
[Humanist Summary](./images/humanist 3.png)

The humanist model evaluates all individuals involved and selects the path that minimizes overall harm, even if it does not prioritize the vehicle’s occupant.

---

### 3. Profit-Based Model (Minimize Cost / Liability)

#### Profiling and Alternative Paths
[Profit Profiling](./images/profit 1.png)

#### Cost Calculation Across Paths
[Profit Calculation](./images/profit 2.png)

#### Final Decision Summary
[Profit Summary](./images/profit 3.png)

The profit-based model assigns cost values to outcomes and selects the path that minimizes financial or liability impact, which may not align with ethical harm minimization.

---

### 4. Protectionist Model (Prioritize Passenger Safety)

#### Profiling and Decision Paths
[Protectionist Profiling](./images/protectionist 1.png)

#### Final Decision Summary
[Protectionist Summary](./images/protectionist 2.png)

The protectionist model prioritizes the safety of the vehicle’s occupant, even when this increases risk to others in the environment.

---

## Key Insights

- **Ethical instability in multi-agent systems**  
  Protectionist systems that prioritize their own occupants become unstable when interacting with similar systems, leading to conflict and increased overall risk.

- **Limits of communication between systems**  
  Communication between vehicles does not resolve ethical conflicts unless underlying decision rules allow for coordination beyond self-interest.

- **Ethics vs localization**  
  Allowing ethical frameworks to vary by geography or user choice risks inconsistency, inequality, and manipulation of outcomes.

- **Law vs ethics gap**  
  Strict adherence to traffic rules does not guarantee the most ethical outcome in emergency scenarios.

---

## Context

As AI systems become more agentic and operate in shared environments, ethical decision-making can no longer be treated as an isolated problem. Systems must be evaluated in the context of **interaction, coordination, and systemic risk**, not just individual behavior.

This work highlights how seemingly reasonable decision rules can produce unintended consequences when scaled across multiple autonomous agents.

---

## Full Write-up

The complete analysis is available here:  
[Written Critique – Ethical Autonomous Vehicles](./critique.pdf)

---
## Source / Simulation Environment

This analysis is based on a simulated ethical decision-making environment for autonomous vehicles, where different moral judgment algorithms are tested across high-risk scenarios.

Video reference:  
https://vimeo.com/236279998

---
