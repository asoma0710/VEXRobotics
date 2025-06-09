# 🤖 VEX Robotics: High Stakes 2024–25

## 🏁 Overview

This repository documents our journey and design decisions for the **VEX High Stakes Competition (2024–25)**. As a team, we designed and built **two distinct robots** to handle the dual challenges in this year's game:

- 🔵 **Bot A**: Designed to **grab rings, stack them on stakes**, and **move stakes** to designated zones.
- 🟢 **Bot B**: A compact and agile climber built to **ascend the elevation bars** for high-scoring endgame bonuses.

---

## 🧠 Initial Game Analysis

This year's game, **High Stakes**, shares several similarities with a previous VEX game — *Tipping Point*. Our strategy builds on familiar concepts like:

- **Mobile Goals** — now needing to be maneuvered into corner zones instead of onto platforms.
- **Ring Handling** — with larger, heavier rings and tighter stake placements.
- **Elevation Tiers** — three levels (3, 6, and 12 points) offering endgame score boosts.

---

## 🛠️ Design Notes & Strategy

### 🔷 Mobile Goals & Rings

- Rings this season are **larger** and **heavier** than in previous games.
- The **stakes require forceful ring placement**, demanding a **robust intake system** — likely a powered claw or intake funnel.
- Mobility is crucial: fast, reactive movement to beat the opposing team to stakes.

📌 *Example ring image:*  
<img src="https://github.com/asoma0710/VEXRobotics/blob/main/media/high_stakes_redring.webp" alt="Ring Image" width="400"/>

---

### 🟡 Elevation Bot (Bot B)

- We are exploring a **4-bar/6-bar lift** or **flex-wheel mechanism** for climbing.
- Level 3 elevation (12 points) offers a great advantage, though it will be prioritized *after* ring and stake scoring optimization.

📌 *Elevation bar layout image:*  
**[Insert Elevation Bar Image Link Here]**

📌 *Example of a level 3 elevation success:*  
**[Insert Level 3 Climb Image or Video Link Here]**

---

### 🚗 Drivetrain Design

- A solid drivetrain is non-negotiable.
- We are considering **4 or 6 omni-directional wheels**, depending on final weight.
- Minimum **4 motors** on the drivetrain for speed and to minimize motor burnout.
- Lightweight design is favored for maneuverability, but layout space is also a concern.

---

## 🤝 My Role

I actively participated in the **initial design phase** of both robots and contributed to:

- Identifying required mechanisms based on the game manual.
- Researching past designs via YouTube/VEX forums.
- Strategizing robot roles and trade-offs between scoring and reliability.

---

## 🧪 Current Development Status

### 🔹 Bot A (Rings + Stakes)

- ✅ Manual control works for grabbing and moving stakes.
- 📹 **Bot A Manual Mode Demo:**  
  [![Watch Video](https://img.youtube.com/vi/uc48Un5ns_c/hqdefault.jpg)](https://youtube.com/shorts/uc48Un5ns_c)
- 🔄 Currently working on **autonomous mode**, including:
  - Onboard **GPS tracking**
  - **Team-color ring identification**
  - **Obstacle avoidance** using rangefinders
  - **Vision sensor integration** for navigation and ring pickup

📸 **Design image of Bot A:**  
**[Insert Image Link Here]**

---

### 🔸 Bot B (Elevation Climber)

- Conceptual frame and lift system are in testing.
- Prioritizing weight balance and consistent grip for level 3 climbs.

📸 **Design image of Bot B:**  
**[Insert Image Link Here]**

---

## 💬 Contributions & Ideas Welcome

These designs are based on careful review of the game manual, competitor strategies, and past VEX competitions.  
We welcome feedback and suggestions to refine our bots further.

> *“Would love anyone else’s opinion on these and any more design ideas that could lead to a successful robot/s.”*  
> — **Gus B**

---

## 📂 Media Gallery

| Media Type       | Description                           | Link/Status                      |
|------------------|---------------------------------------|----------------------------------|
| 📷 Bot A Design   | Ring + Stake Handler (Primary Bot)    | [Insert Image Link]              |
| 📷 Bot B Design   | Climber Bot (Endgame)                 | [Insert Image Link]              |
| 📹 Bot A Video    | Manual Mode Test                      | [Insert YouTube Link]            |
| 📷 Elevation Bar  | Field Element Measurement             | [Insert Image Link]              |
| 📹 Level 3 Climb  | Example Success                       | [Insert YouTube Link]            |

---

## 📘 Additional Notes

- Game Manual Reviewed: ✅  
- Field Layout Studied: ✅  
- Competition Goals Set: 🏆 Score high with stakes and rings first, then climb.

---

## 📅 Roadmap (Next Steps)

- [ ] Finalize Autonomous GPS Routing  
- [ ] Improve Ring Detection via Vision Sensor  
- [ ] Tune Climber Weight Balance  
- [ ] Test Full Match Strategy  

---

## 🔗 Useful Links

- [VEX Forum](https://www.vexforum.com/)  
- [VEX High Stakes Official Manual](https://www.vexrobotics.com/)  
- [VEXCAD & Design Archive](https://www.vexcad.com/)

---

> Designed with passion by our 2024–25 VEX Robotics Team @ MSU 🏁

