# 🚑 Code Blue – ER Decision-Making Game

**Code Blue** is a browser-based emergency room (ER) simulation game built for  
**BME3053C – Computer Applications for Biomedical Engineering**.

The game puts players in the role of an ER doctor responsible for:
- Moving between patients
- Assigning urgency levels
- Choosing treatments under time pressure  
to mirror the stress and multitasking of real emergency workflows.

---

## 🎮 Gameplay Overview

In **Code Blue**, you manage multiple patients in an ER setting.  
Each patient presents with a short case description (symptoms, vitals, context).  

Your job is to:
1. **Navigate** to the patient
2. **Assign an urgency level**
3. **Choose and perform the correct treatment**
4. **Do all of this before time/health runs out**

Your decisions affect:
- **Score**
- **Patient outcomes**
- **Overall success of the level**

---

## 🕹 Controls

> 🔧 Update this section to match your actual keybinds

- **Move**: `W`, `A`, `S`, `D` (or arrow keys)
- **Interact / Talk to Patient**: `E`
- **Confirm Decision / Select Option**: `Enter` or click with mouse
- **Switch Tabs / Views (if applicable)**: Click interface buttons at top

Mouse is used for:
- Choosing urgency levels
- Selecting treatments
- Navigating UI buttons (tabs, start, restart, etc.)

---

## 🩺 ER Workflow in the Game

Code Blue is designed around a simplified ER workflow:

### 1. **Arrival & Presentation**
Each patient appears with:
- A brief scenario (e.g., chest pain, trauma, altered mental status)
- Key findings (vital signs, general appearance, history clues)

Your first task is **rapid assessment**.

### 2. **Assigning Urgency**

You must assign a triage/urgency level based on the case:

- If you **over-triage** (low severity marked as high),  
  → small point penalty but the patient is safe.

- If you **under-triage** (high severity marked as low),  
  → larger penalty and the patient’s status worsens.

- Taking too long to decide drains the **time/health bar**,  
  modeling how real-life delays can harm outcomes.

### 3. **Treatment Selection**

Once urgency is set, you choose the correct intervention(s), such as:
- Starting CPR
- Giving fluids
- Providing oxygen
- Ordering appropriate tests/next steps (simplified in-game)

Picking the wrong treatment or hesitating:
- Costs time
- Lowers score
- Can cause the case to “crash” or fail

### 4. **Progression Through Cases**

As you move through the game:
- Cases become more complex
- Time pressure increases
- Multitasking and prioritization become more important

The player learns to:
- Scan information quickly
- Prioritize high-risk patients
- Commit to decisions under pressure

---

## 🎯 Learning Objectives

Code Blue was built to reinforce:

- **Fast recall** of basic medical and physiological concepts  
- **Prioritization** of patients based on severity and time sensitivity  
- **Multitasking** in a simulated, high-stress ER environment  
- **Critical thinking** when information is limited

It is **not** a clinical training tool, but a **learning experience** to:
- Illustrate ER workflow
- Practice structured decision-making
- Appreciate how “every second counts” in emergent care

---

## 📦 How to Run the Game

1. **Clone or download** this repository:
   ```bash
   git clone <YOUR_REPO_URL_HERE>
   

