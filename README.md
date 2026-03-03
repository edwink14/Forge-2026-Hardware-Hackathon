# Forge-2026-Hardware-Hackathon
Arduino-powered WiFi-controlled basketball robot built for a timed hackathon challenge, featuring precision micro-adjust movement and a PWM-driven catapult shooting system using an L298N motor driver.

Built by Edwin Kintu, Awab Choudhury, Justin Ferreira, Charles Wang, and William Zhang.

# 🚀 Overview
LeBot is a remotely controlled robot car featuring:
- WiFi control (Access Point mode)
- Precision micro-adjustment movement system (left, right, back, front)
- Motorized catapult shooting mechanism

# ⏱ Competition Constraints
- 15 mins to collect as many points as possible
- 5 min (Moving Basket Challenge)
- Must reposition after 3 successful shots
- -1 point penalty for shooting outside the field
- Dunking not allowed
The robot was optimized for fast repositioning and repeatable shot strength.

# 🧰 Hardware
- Arduino board
- L298N motor driver
- 2 DC drive motors
- 1 DC motor (catapult system)
- 3D-printed arm mechanism
- Chassis + wheels
- 2 9V battries
🧠 System Design

# 🔹 Movement System
Instead of continuous drive, the robot uses short high-power PWM bursts (80ms) to:
- Overcome friction instantly
- Allow fine micro-adjustments
- Hard brake immediately for precision aiming
This significantly improved shot alignment during competition.




