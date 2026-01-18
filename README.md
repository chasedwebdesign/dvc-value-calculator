# DVC Value Magician 🏰✨

A free, open-source calculator that determines if you should **Rent DVC Points** or book a **Disney Cash Reservation**.

### 🚀 [Launch the Calculator](https://dvcpointcalc.netlify.app/)

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Status](https://img.shields.io/badge/Disney-Magic-orange.svg)

---

## 🧐 The Problem
Disney Vacation Club (DVC) point charts are confusing. Travelers often ask:
* *"Is it actually cheaper to rent points?"*
* *"What is the 'Implied Value' of a point for this specific hotel stay?"*
* *"Does the lack of daily housekeeping justify the 40% savings?"*

I built this tool to strip away the marketing and show the raw math.

## ⚙️ How it Works
The calculator uses a comparison logic to find the "Break Even" point:

```math
Implied Value = (Cash Price from Disney) / (Points Required)
