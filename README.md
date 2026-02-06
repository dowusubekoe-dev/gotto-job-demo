# 📑 Project: Gotto Job — UI Polish Sprint

**DMI DevOps Bootcamp | Assignment 4**

## 🎯 Overview

This project involved a full **Scrum Lifecycle** simulation on the "Gotto Job" platform. As a solo practitioner playing all four key Scrum roles, I moved the project from a raw product backlog to a live, verified UI increment deployed on **AWS EC2**.

---

## 👥 Roles & Responsibilities

To simulate a professional environment, the following roles were performed:

* **Product Owner (PO):** Defined the vision and prioritized the backlog based on user "Discoverability and Trust."
* **Scrum Master (SM):** Facilitated ceremonies, managed the Jira board, and monitored the Burndown Chart.
* **Dev Lead:** Executed the HTML/CSS changes and performed local responsive validation.
* **DevOps Lead:** Managed the Git flow, handled Pull Requests, and deployed the final build to production.

---

## 🛠️ Sprint 1 Execution (Jira)

### 1. Backlog Refinement

I seeded the Product Backlog with 6 high-value User Stories. Each story was estimated using **Fibonacci points (1, 2, 3)** to gauge effort and complexity.

| Story | Points | Role Responsible | Status |
| --- | --- | --- | --- |
| **Hero Tagline Clarity** | 1 | PO / Dev Lead | ✅ Done |
| **Primary CTA Color Contrast** | 1 | PO / Dev Lead | 📝 Backlog |
| **Job Card Typography** | 2 | Dev Lead | 📝 Backlog |
| **REMOTE Badge UI** | 2 | Dev Lead | 📝 Backlog |
| **Posted Date Implementation** | 1 | PO / Dev Lead | 📝 Backlog |
| **Footer Trust Links** | 1 | PO / DevOps | 📝 Backlog |

### 2. Sprint Planning

* **Sprint Goal:** "Ship a visible UI improvement to the Hero section and verify cloud deployment."
* **Scope:** Selected the **Hero Tagline Clarity** story (1pt).
* **Sub-tasks:**
1. **Build:** Update `index.html` with the tagline: *"Find your next role, fast."*
2. **Verify:** Test mobile responsiveness using DevTools.
3. **Deploy:** Transfer files to EC2 and reload Nginx.
4. **Screenshot:** Document proof for the stakeholder review.



---

## 🚀 Shipping the Increment (DevOps Workflow)

### The Technical Process

1. **Branching:** Created `feature/hero-tagline` from `main`.
2. **Implementation:** Updated the Hero section in the source code.
3. **Local Validation:** Ensured text wrapped cleanly on mobile viewports.
4. **Version Control:** ```bash
git add .
git commit -m "feat(ui): update hero tagline for clarity and impact"
git push origin feature/hero-tagline
```

```


5. **Deployment:** Pushed to the **AWS EC2** instance and verified live at the public IP.

---

## 📊 Sprint Reports & Metrics

### Burndown Chart

The Burndown Chart was utilized to track the team's velocity. By breaking the story into granular sub-tasks, I maintained **Transparency** throughout the sprint, ensuring the "Burn to Zero" was completed on time.

---

## 📝 Sprint Retrospective

* **What Went Well:** The **Triangular Git Workflow** (Upstream > Origin > Local) ensured zero merge conflicts.
* **What to Improve:** Estimation for CSS-heavy tasks should account more for cross-browser testing time.
* **Scrum Pillar:** **Inspection** — Used the Burndown chart to detect potential delays early.
* **Scrum Value:** **Focus** — The team successfully ignored "extra" UI tweaks to deliver the committed Hero increment.

---

## 🔗 Live Deliverables

* **Live Portfolio URL:** `http://98.91.26.137/`
* **Jira Project Board:** `https://derekowusubekoe-dmi.atlassian.net/browse/GJDOB-1?atlOrigin=eyJpIjoiYzQwZjIwNThmMDdjNGEyZjg2Y2IxZjkyMmE3NWU0ODgiLCJwIjoiaiJ9`
* **LinkedIn Proof:** `[Link to your LinkedIn Post]`

---

**Is there anything else you'd like to add to this README, perhaps a section on the specific CSS contrast ratios you used?**