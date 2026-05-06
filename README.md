# 🎰 Lottery Trainer

> A convenience store lottery terminal training simulator — built to survive the job.

**Live App → [alock2103.github.io/Lottery-Trainer](https://alock2103.github.io/Lottery-Trainer)**

---

## What is this?

A browser-based training tool that simulates a real OLG lottery terminal. Customers give you orders — you figure out the right game, boards, draws, and add-ons. Built for real convenience store workers learning the terminal from scratch.

All game names are renamed for legal purposes (Lotto Max → Lotto Macks, etc.)

---

## Games Included

| Trainer Name | Real Name | Parameters |
|---|---|---|
| Lotto Macks | Lotto Max | Boards, Draws, Encore |
| Lotto 6/50 | Lotto 6/49 | Boards, Draws, Encore, Add-on |
| L'Ontario 50 | Ontario 49 | Boards, Draws, Encore |
| Lightning Lotts | Lightning Lotto | Boards (1–5) |
| Joker Lotto | Poker Lotto | Selections, Add-on |
| Power Bux | Power Bucks | Boards, Draws |
| Wheel of Riches | Wheel of Fortune | Boards, Spins |
| Card Lotto | Poker variant | Selections, Add-on |
| Duo Pick | Pick 2 | Play Type, Wager, Draws |
| Triple Pick | Pick 3 | Play Type, Wager, Draws |
| Quad Pick | Pick 4 | Play Type, Wager, Draws |

---

## Difficulty Levels

| Level | Description |
|---|---|
| 🟢 Easy | Clear standard English |
| 🟡 Medium | Casual with some slang |
| 🔴 Hard | Heavy slang, curses, Canadian expressions |
| 💀 Ich Will Sterben | Pure chaos. Self-corrections, contradictions, and suffering. |

---

## Modes

- 📝 **Text Only** — Read the customer order
- 🔊 **Voice Only** — Hear it spoken (male or female voice, randomized) — text hidden until you answer
- 🎲 **Random Mix** — Alternates between text and voice

---

## How to Use

1. Select difficulty and mode on the start screen
2. Read or listen to the customer order
3. Click the correct game tab at the top
4. Set the right parameters (boards, draws, encore, etc.)
5. Hit **Print Ticket**
6. Check your attempt circles — click any circle to see what you got right or wrong

---

## Tech

Single `index.html` file. No backend. No API key. No install.
Uses React 18 (CDN), Web Speech API for voice, pure JS sentence generation.

---

*For training purposes only. Not affiliated with OLG or any lottery corporation.*
