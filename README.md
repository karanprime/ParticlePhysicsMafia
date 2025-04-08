# ⚛️ Particle Physics Mafia

Welcome to **Particle Physics Mafia** – a chaotic social deduction game where the standard model meets good old-fashioned betrayal. Matter and antimatter are at war, and only clever deduction (or particle annihilation) will lead to victory.

Inspired by the classic Mafia/Werewolf party games, each player assumes the identity of a subatomic particle, complete with unique abilities. Your job? Either uncover the lurking antimatter or bring all of matter to decay.

---

## 🚀 Quick Start

This is a **role-based social deduction game** for large groups, best with 15–25 players. Designed for in-person or online play (voice/video strongly recommended).

Each player is secretly assigned a particle role, drawn from either the **Matter** team (Town) or the **Antimatter** team (Mafia). The game alternates between **Unobserved Phases** (night) and **Observed Phases** (day), where players use abilities and vote to eliminate others.

---

## 📦 Repository Structure
- **`cards/`** – PNG images of each particle card, suitable for digital play or preview.
- **`source/`** – LaTeX source files for generating the PDFs. Modify card text, abilities, or add your own roles.
- **`pdfs/`** – Print-ready PDFs with cards sized to standard **Magic: The Gathering** dimensions (63mm x 88mm).

---

## 🧍‍♂️ Matter Roles (Town)
- **Electron (x2)** – *Detective*: Learns the electric charge of a chosen particle.
- **Photon (x1)** – *Watcher*: Sees all particles that interacted with a chosen one during the unobserved phase.
- **Up Quark (x5)** – *Mason*: Knows the identities of other quark-aligned particles.
- **Charm Quark (x5)** – *Mason*: Same as above.
- **Down Quark (x5)** – *Outsider*: Knows the quark group but has a negative charge.
- **Electron Neutrino (x1)** – *Little Girl*: Can peek into the antimatter group during unobserved phases (risky).
- **W Boson (x1)** – *Doctor*: Protects one particle from being put into the collider.
- **Higgs Boson (x1)** – *Jailer*: Blocks a particle's actions and protects them.
- **Muon (x2)** – *Insane*: May force any one player into the collider (lynch) once per game.
- **Tau (x1)** – *Vigilante*: Can put someone in the collider each night. If they target a matter particle, they decay (die).
- **Gluon (x5)** – *Amor*: Helps bind the quarks together — thematic/flavorful, can be used to pair players as bonded (lovers-style optional rule).

### ☢️ Antimatter Roles (Mafia)
- **Anti-Up Quark (x4)** – *Standard Mafia Member*
- **Anti-Top Quark (x1)** – *Mafia Boss*: Breaks ties and has final vote authority.
- **Anti-Down Quark (x2)** – *Godfather*: Antimatter that reads as positive when investigated.

---

## 🎲 Game Overview

### Observed Phase (Day)
- Players debate and vote on whom to send to the **Collider** (lynch).
- Majority vote causes a particle to decay (removed from the game).
- Their role is revealed.

### Unobserved Phase (Night)
- Players with powers use them secretly.
- Antimatter team chooses a target to annihilate.
- The GM narrates what happened.

### Win Conditions
- **Matter wins** when all Antimatter particles are eliminated.
- **Antimatter wins** when they equal or outnumber Matter.
- **Optional**: If Gluon-bonded quarks are alive at the end, they win together.

---

## 🧠 Optional Rules

- **Gluon Bonding**: Secretly creates hadrons. Can select a trio of Up, Down Charm Quarks. If one dies, the others die too.
- **Muon Mayhem**: Each Muon can force a lynch once per game.
- **Charge Confusion**: Anti-Down particles appear positive when scanned by the Electron.

---

## 🛠️ LLM Usage

All roles and their particle-flavored abilities were created by the team. We used LLMs to help:

- Generate card artwork based on role descriptions
- Write this README

The creativity and flavor are human-made, the visuals are AI-assisted. ✨

---

## 👨‍🔬 Authors

This game was created for the **MLMD CASUS Get-Together** by:

**Bartosz Brzoza** and **Karan Shah**  
_Machine Learning for Materials Discovery Group_  
[Center for Advanced Systems Understanding (CASUS)](https://www.casus.science/)  
Görlitz, Germany

---

## 📘 License

MIT License – remix, reprint, and collide freely.

---

## 👩‍🔬 Contribute

Ideas for new particles, roles, or mechanics are welcome! Feel free to submit pull requests or open issues.

---
