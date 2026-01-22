# syncing-backingtrack

🧮 **Theoretical / Conceptual Project**

## Overview

**syncing-backingtrack** is a conceptual project derived from my microrhythm research, applied to **live music performance** contexts.

The project addresses a common issue in contemporary performance practice: maintaining synchronization between live musicians and pre-produced backing tracks without sacrificing expressive freedom.

---

## Motivation

Through live performance experience and collaboration with musicians from diverse backgrounds, I have observed that synchronizing to a metronome is not only a learned skill, but also a matter of individual aptitude.

In many cases, strict adherence to a click track constrains musical expression, while performances without a click allow greater interaction, flexibility, and responsiveness among musicians.
This project explores a middle ground between these two extremes.

#### Maintining microrhythmic relations within backing track

When adapting material derived from my microrhythm research to live performance contexts, I had the opportunity to work with a drummer capable of following a metronome exhibiting distinct microrhythmic tendencies.

In the context of this project, however, when the backing track is dynamically adapted to the drummer’s tempo, it is essential that the internal microrhythmic relations of the backing track are preserved. These relations may be integral to the stylistic identity of the material and to the structural integrity of the original composition.

---

## Goals

Designing an algorithm that:

- Receives a **stable real-time signal** from a drummer (or rhythmic leader)
- Extracts onset information and continuously analyzes **inter-onset interval (IOI)** values
- Estimates tempo fluctuations in real time
- Dynamically **stretches or compresses a backing track** so that it adapts to the performer’s timing rather than enforcing a fixed tempo

The main goal is to allow the backing material to **follow the musician**, preserving expressive timing while maintaining synchronization.

---

## Tools (planned)

- **Python** (real-time and offline analysis)
- **Essentia** (onset detection, tempo estimation)
- **Digital Signal Processing (DSP)** techniques for time-stretching
- **REAPER** (prototyping and evaluation environment)
- Optional real-time systems: SuperCollider or similar

---

## Status

**Status:** 🧮 Future Development  

This project is currently theoretical and intended for exploration **during/after a Sound and Music Computing (SMC) Master**, as part of ongoing research into rhythm, timing, and expressive performance systems.

---

## License

All rights reserved. This repository is made public for viewing and academic evaluation purposes only.
