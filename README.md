# Shelter 3D: From the Moon to Home

A browser game that teaches young people to think like mission engineers. You pack one rocket for a base on the Moon or Mars, keep four astronauts alive for 28 days, and then use the same science to protect a 3,000-year-old royal mummy in Cairo.

**Play it:** open `index.html` in a modern browser, or visit the GitHub Pages link for this repository.

> This is an improved version built **after** our NASA Space Apps Challenge 2026 submission. Our official hackathon entry is the 2D game *Shelter: From the Moon to Home*.

---

## How to play

### 1. Pack the rocket
Choose the Moon or Mars and a difficulty level. Each item costs cargo points, and you can't take everything.

| Item | What it does |
|---|---|
| 🪞 Multi-layer insulation (MLI) | Reflects heat. Used on satellites. |
| ☁️ Aerogel panel | About 99% trapped air. Used on Mars rovers. |
| ⛰️ Regolith cover | Local soil on the roof. Insulates and blocks radiation. |
| ☀️ Solar panel | Free power, but only in sunlight. |
| 🔋 Battery | Stores power for the night. |
| ⚛️ Fission reactor | Power day and night (Kilopower-class). |
| 🌱 Greenhouse | Grows food, but needs power and warmth. |
| 📦 Food crate | 8 crew-days of packed food. |
| 🛡️ Storm shelter | Cuts solar-storm radiation by 90%. |

### 2. Survive 28 days
Assign each crew member to a job: Nour (engineer), Omar (botanist), Laila (scientist) and Yusuf (doctor). Handle emergencies such as meteoroid strikes, solar storms, Martian dust storms, heater failures and sickness.

**Goals:**
- Survive 28 days.
- Collect enough science points.
- Keep crew health at 70 or more.

### 3. Mission Earth: protect the king
Design a museum display case for a royal mummy with a 30-point budget. Then keep it between 20 and 24°C, with humidity between 45 and 50%, through 3 summer days in Cairo. A heatwave, a power cut and a school trip will test your design.

### 4. Earn your certificate
Win the missions to unlock a full-screen certificate with your name. You can print it or save it as a PDF.

---

## The science

**Heat loss = area × temperature difference ÷ R-value**

- **Moon:** the night lasts about 14 Earth days and drops to about −170°C. Batteries alone would be too heavy, so a reactor makes sense.
- **Mars:** nights are about 12 hours long, so solar panels and batteries can work. Sunlight is weaker, though, and dust storms can cover the panels.
- **Radiation:** about 1.4 mSv/day on the Moon's surface and about 0.67 mSv/day on Mars.
- **Mummy hall:** the same ideas apply on Earth. Resistance (R-value) slows heat, thermal mass stores it, and backup power plans for failures.

Our team also built a real prototype: a 15 × 15 cm box with a 30 mm six-layer roof panel (clay–rice husk, air gap, foil, cardboard, cork, cardboard). Our calculation shows it lets in about 62% less heat than a plain cardboard lid.

---

## Sources

- Lunar surface temperatures: NASA Lunar Reconnaissance Orbiter (Diviner)
- Lunar surface radiation: Chang'e-4 lander (*Science Advances*, 2020)
- Mars surface radiation: NASA Curiosity rover (RAD)
- Mars temperatures: NASA Curiosity and Perseverance rovers
- Astronaut career radiation limit of 600 mSv: NASA (2022)
- Reactor concept: NASA Kilopower / Fission Surface Power
- Mummy hall conditions (about 20–22°C, at most 24°C, humidity 45–50%): Egyptian museum conservators, reported by Asharq Al-Awsat
- Nitrogen-sealed royal mummy cases: Getty Conservation Institute

Game values are simplified for learning.

---

## Built with

- HTML, CSS and JavaScript in a single file
- [three.js](https://threejs.org/) for 3D graphics
- English and Arabic interface

## AI disclosure

We used AI tools to help write the code and visuals. Our team chose the challenge and the idea, designed the trade-offs, selected the science and sources, built the physical prototype, and tested the game.

## Team

Team ______: NASA Space Apps Challenge 2026, Egypt
