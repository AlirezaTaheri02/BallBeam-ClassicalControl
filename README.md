# Stability Control of the Ball-&-Beam System

This repository contains my implementation of the **BallStab** project, developed as part of the *Automatic Control course (2023)*.  

BallStab focuses on modeling, linearizing, and controlling a **nonlinear ball-&-beam system** using classical control strategies in MATLAB/Simulink.

##  Overview
Key aspects of the project:
- Modeled a **nonlinear ball-&-beam system** with two degrees of freedom: beam angle (θ) and ball position. 🎯
- Linearized system equations around equilibrium and obtained **transfer functions** for simulation. ⚡
- Implemented and compared classical controllers: **P, PI, PD, PID, Lead–Lag**. 🛠️
- Conducted **time-domain analysis** and tuning for fast, stable, and overshoot-free response. ⏱️  

The project demonstrates how classical controllers behave on a nonlinear system and how linearization enables simulation-based design.

## 📷 Visual Demonstrations (images + tags)

Below are the screenshots from MATLAB/Simulink and analysis plots.  
Place the image files in the repository folder `assets/` and ensure filenames match exactly.

| Image file (assets/) | Tags | Caption |
|---|---:|---|
| `simulink-model.png` | `Simulink`, `modeling`, `ball-beam`, `system` | MATLAB/Simulink model of the nonlinear ball-&-beam system. |
| `linearization.png` | `linearization`, `transfer-function`, `equilibrium` | Linearized system transfer function around equilibrium. |
| `pid-response.png` | `PID`, `control`, `time-domain`, `tuning` | PID controller response showing stable ball positioning. |
| `controller-comparison.png` | `P`, `PI`, `PD`, `PID`, `Lead-Lag` | Comparison of classical controllers on system stability and performance. |

---

### Inline images with captions

### 🏗️ Simulink Modeling
Nonlinear system modeled with two degrees of freedom.

<figure>
  <img src="assets/simulink-model.png" alt="Ball-&-Beam Simulink Model" />
  <figcaption><strong>Simulink Model</strong> · Tags: <code>Simulink</code>, <code>modeling</code>, <code>ball-beam</code>, <code>system</code></figcaption>
</figure>

---

### ⚡ Linearization & Transfer Function
Linearized system enables controller design and simulation.

<figure>
  <img src="assets/linearization.png" alt="Linearized Transfer Function" />
  <figcaption><strong>Linearization</strong> · Tags: <code>linearization</code>, <code>transfer-function</code>, <code>equilibrium</code></figcaption>
</figure>

---

### 🛠️ Controller Implementation & Comparison
Implemented P, PI, PD, PID, and Lead–Lag controllers; tuned for fast and stable response.

<figure>
  <img src="assets/pid-response.png" alt="PID Controller Response" />
  <figcaption><strong>PID Response</strong> · Tags: <code>PID</code>, <code>control</code>, <code>time-domain</code>, <code>tuning</code></figcaption>
</figure>

<figure>
  <img src="assets/controller-comparison.png" alt="Controller Comparison" />
  <figcaption><strong>Controller Comparison</strong> · Tags: <code>P</code>, <code>PI</code>, <code>PD</code>, <code>PID</code>, <code>Lead-Lag</code></figcaption>
</figure>

---
