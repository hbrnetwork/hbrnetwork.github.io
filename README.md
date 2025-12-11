# HomeBrew Robotics Network (HBRN)
**Community for Building the “PC of Robotics”**

> _“The HomeBrew Robotics Network is a global extension of the HomeBrew Robotics Club, which is to robots what the Homebrew Computer Club was to PCs.”_

This repo hosts the source for the **HomeBrew Robotics Network website** and related materials (logo, landing page, docs). 

HBRN is a decentralized, open, community-driven effort to make **helpful low-cost household robots as ubiquitous and hackable as personal computers.**

<p align="center">
  <img src="assets/hbrn-logo.png" alt="HomeBrew Robotics Network logo" width="260">
</p>

---

## Why HBRN?

The personal computing revolution started with:

- cheap DIY kits (Altair 8800),
- hobbyist clubs (Homebrew Computer Club),
- and open standards (IBM PC, BASIC, Unix).

Today robotics is at a similar inflection point:

### _Historical Price Trends in Mobile Manipulation_

| **Type** | **Before 2020** | **2025** | **2025 (DIY)** |
|---------|------------------|----------|-----------------|
| **MoMa** (Mobile Manipulation) | [Fetch ($100k)](https://robotsguide.com/robots/fetch) | [HelloRobot Stretch ($25k)](https://hello-robot.com/stretch-3-product) / [TidyBot++ ($35k)](https://tidybot2.github.io/docs/) | [LeKiwi ($1k)](https://github.com/SIGRobotics-UIUC/LeKiwi) |
| **BiMoMa** (Bi-Manual Mobile Manip.) | [PR2 (> $200k)](https://www.wevolver.com/specs/pr2) | [Trossen Mobile AI ($35k)](https://www.trossenrobotics.com/mobile-ai) | [ALOHA ($30k)](https://mobile-aloha.github.io/) / [XLe (< $1k)](https://xlerobot.readthedocs.io/en/latest/) |
| **Humanoid** | [ASIMO (> $1M)](https://en.wikipedia.org/wiki/ASIMO) / [Atlas ($160k)](https://bostondynamics.com/contact/) | [Unitree G1 ($16k)](https://shop.unitree.com/products/unitree-g1) / [1X Neo ($20k)](https://www.1x.tech/order) | [UCB Humanoid Lite (< $5k)](https://lite.berkeley-humanoid.org/) |

_Table 1: Price comparison of commercial and DIY mobile manipulation systems.  
MoMa: Mobile Manipulation. BiMoMa: Bi-Manual Mobile Manipulation._

Open-source frameworks like [LeRobot](https://lerobot.org/) are early attempts at a shared “robot stack.”

What’s missing is a **network**: open community, shared standards, a common culture, and a place for builders to collaborate.

**HBRN exists to fill that gap.**

---

## Mission

> **Build the PC of Robotics through open hardware, software, standards, and grassroots communities.**

We imagine a world where:

- helpful robots can **carry, assemble, clean, cook, and entertain**,  
- they are **affordable**, **programmable**, and **present in every home**,  
- no single closed company can out-innovate a global community of builders.

---

## Guiding Principles

- **If something isn’t right, change it.**  
  _Inspired by Wikipedia_

- **Decentralized to last.**  
  _Inspired by the early Internet & Bitcoin_

- **Open to the core and community-driven.**  
  _Inspired by Linux_

---

## The HBRN Architecture: Three Layers

HBRN is organized around three mutually reinforcing layers.

### 1. Community Layer  
_HBRC + University / Regional Nodes_

The foundation is a distributed network of clubs, labs, and hackerspaces:

- **Core nodes:**  
  - [HomeBrew Robotics Club (HBRC)](https://www.hbrobotics.org/) — founded in 1984 as a spiritual successor to the original Homebrew Computer Club.
  - [LeRobot](https://lerobot.org/) - started by Hugging Face in 2024, serving as a modern open-source community for models, datasets, and tools for real-world robotics.

- **Regional & university nodes (examples):**
  - **West Coast:** UC Berkeley, Stanford  
  - **Midwest:** Rice University, UIUC  
  - **Northeast:** MIT, Northeastern, Columbia  
  - **Southeast:** University of Miami, University of South Florida
  - and growing... 

Planned community channels:

- shared Discords/Mailing Lists  
- monthly meetups & hack nights  
- cross-node demos and student pipelines  
- a national **“HomeBrew Robotics Network Meetup”** series  

The goal is to make it easy to **find collaborators, share designs & code, and converge on emerging standards.**

---

### 2. Infrastructure & Standards Layer  
_The “Microsoft + IBM” layer of robotics_

Robotics today is fragmented: many ad-hoc ROS stacks, custom drivers, and bespoke teleop pipelines.

HBRN aims to define the **shared abstractions** that make robots programmable like PCs.

#### Software Standards (DOS-like)

Open problems we want to tackle together:

- A **composable policy / operator learning** framework for teleop, imitation, and autonomy  
- A **unified behavior-programming API** across robots  
- Common **controller & driver interfaces** for heterogeneous hardware  
- A lightweight, household-robot-focused **runtime / OS**

#### Hardware Standards (IBM-like)

Complementing the software stack:

- Reference open architectures for **mobile manipulation** and **humanoids**  
  (e.g., XLe, Humanoid Lite)
- Standardized **actuator, sensor, and communication** interfaces  
- A crisp definition of the **HuBiMoMa** class:  
  _Humanoid / Bi-manual / Mobile Manipulator_

Together these form the backbone of an open robotics ecosystem, analogous to **BASIC + Unix/Linux + MS-DOS + IBM PC** for computers.

---

### 3. Ecosystem Layer  
_Open, modular companies_

On top of shared standards, we expect a vibrant ecosystem of **interoperable niche players**, not one monolithic stack:

- Hardware: Unitree, 1X, Apptronik, Hello Robot, Low-Cost DIY 
- Software: model providers, planning stacks, simulation, teleop tools  
- Education: kits, curricula, training programs  
- Verticals: eldercare, logistics, household services, small-business robotics

If you’re building in this space, HBRN is a place to **align with standards**, not a competitor.

---

## Who Is This For?

- **Students & hobbyists** building DIY robots in garages, clubs, or dorms  
- **Researchers & labs** working on low-cost manipulation and humanoids  
- **Open-source contributors** building drivers, planners, and learning pipelines  
- **Companies & nonprofits** who want interoperable, open robotics standards

If you see “Altair-era” energy in current robotics, you’re in the right place.

---

## Getting Started

1. **Visit the site**  
   This repo backs the HBRN GitHub Pages site (e.g. [`hbrnetwork.github.io`](https://hbrnetwork.github.io/)).  
   Open it in your browser to see the latest landing page, events, and docs.

2. **Join or start a node**
   - Already part of a robotics group on the [Discord](https://discord.gg/jGWZzaQwqt)? Add yourself as a regional node.
   - Want to start a **HomeBrew Robotics Network meetup** in your city? Open an issue with:
     - location
     - affiliation (if any)
     - primary contact
     - what you’re working on

3. **Build a reference robot**
   - Try replicating a low-cost platform like XLe, LeKiwi, or Humanoid Lite.
   - Share your **BOMs, build guides, and lessons learned** in this repo or your own, then link back.

4. **Contribute to standards**
   - Propose APIs for teleop, behavior libraries, or drivers.  
   - Add write-ups comparing stacks, documenting best practices, or summarizing papers.

5. **Run events**
   - Host hack nights, reading groups, or live-teleop demos.
   - Share slide decks and recordings via PRs so other nodes can reuse them.

---

## Repository Layout (proposed)

```text
.
├── README.md              # You are here
├── docs/                  # Longer-form design docs & standards
├── index.html             # GitHub Pages / website source
├── hbrn-logo.png
├── examples/              # Example configs, build guides, curriculum
└── org/                   # Templates for new nodes, proposals, etc.
```

---

## Appendix

### _Comparison of Representative Robotics Systems_

| **Group** | **System (Cost)** | **Demo** | **Open** | **BiMaMo** | **Auto** | **LoCo** |
|-----------|-------------------|----------|----------|------------|----------|----------|
| **TeslaAI** | Optimus (TBD) | [Factory](https://www.youtube.com/watch?v=DrNcXgoFv20) | No | Yes | No | No |
| **Figure** | TBD | [Factory](https://youtu.be/WlUFoZstcWg?si=yCCxBH9xAO1XbWbF) | No | Yes | Yes | No |
| **1X** | Neo ($20k) | [Household](https://youtu.be/uVcBa6NXAbk?si=jmwrnVjnsjDz7g4l) | No | Yes | No | Yes |
| **MIT (LIS)** | Spot ($100k) | [Household](https://ees.csail.mit.edu/) | Yes | No | Yes | No |
| **Google (Deepmind XE)** | Mobile ALOHA ($30k) | [Household](https://youtu.be/1oSSex9b6fc?si=ee950w7ZAmAJPaMu) | Yes | Yes | Yes | No |
| **Stanford (π)** | Mobile ALOHA ($30k) | [Household](https://youtu.be/zMNumQ45pJ8?si=AaNHqfHloEvylWXL) | Yes | Yes | Yes | No |
| **Rice (Robotπ)** | XLe (< $1k) | [Household](https://xlerobot.readthedocs.io/en/latest/) | Yes | Yes | No | Yes |

_Table 2: Summary of representative mobile manipulation and humanoid systems and their properties (demo type, open-sourced [OPEN], bi-manual mobile manipulation [BiMaMo] , fully autonomous vs teleoperation [Auto], and low-cost feasibility - less than \$1K [LoCo])._
