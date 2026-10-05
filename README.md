# EDITOR TX816 v1.4 (1988) — Atari ST / GFA BASIC Reconstruction

A web-based reconstruction of **EDITOR TX816 v1.4**, originally developed in **1988** by **Marjan Šijanec** (MS Software) using **GFA BASIC 3** for **Atari ST** computers. 

This program was the first piece of software originally designed for professional use in the legendary **Electronic Studio of Radio Belgrade**—to control, program, and manage the **Yamaha TX816** synthesizer rack.

---

## Historical Significance

### Pioneering Computer Music in Yugoslavia
In the late 1980s, the intersection of microcomputing and professional audio hardware opened up revolutionary possibilities for electroacoustic and contemporary art music. Marjan Šijanec, a prominent composer, developed this software to bridge the gap between emerging personal computing platforms (Atari ST) and high-end studio synthesizers.

### The Yamaha TX816 Monument
The **Yamaha TX816** was a powerhouse of FM synthesis in a 4U rackmount unit. It housed **eight independent TF1 modules**, where each module was essentially a complete **Yamaha DX7** synthesizer engine (without a keyboard or physical front panel). Programming a DX7 from its tiny, menu-driven hardware interface was notoriously complex; programming *eight* of them simultaneously was a daunting task. 

Šijanec’s software acted as an indispensable master control center, allowing sound designers and composers to:
* Visually edit parameters across all 8 independent modules from a single screen.
* Manage complex multi-timbral patches, performance maps, and MIDI channels.
* Handle bulk System Exclusive (SysEx) data dumps between the computer and the hardware rack.

### Studio Heritage (Radio Belgrade)
Tools like *EDITOR TX816* formed the technical backbone of institutional electronic music studios in the region, such as the Electronic Studio of Radio Belgrade. They enabled composers of electroacoustic music to orchestrate complex algorithmic, microtonal, and multi-layered compositions long before modern Digital Audio Workstations (DAWs) and software plugin editors became standard.

---

## About the Web Reconstruction

This project is a faithful single-file HTML/JavaScript reconstruction based on a scanned partial printout of the original GFA BASIC source code listing. 

### Key Features of the Reconstruction:
* **Atari ST GEM Aesthetic:** Recreates the retro monochromatic window environment, dropdown menus, and dialog boxes of the late 80s operating systems.
* **Full 8-Module Architecture:** Complete parameter matrix covering all 6 FM operators, global envelopes, algorithms, and LFO settings for each TF1 module.
* **Web MIDI API Integration:** Connects directly to modern hardware synthesizers or software-based MIDI routings via Web MIDI and SysEx messages.
* **File Management:** Supports loading/saving voice patches (`.vce`), performance setups, and automatic browser-based backup (`localStorage`).

---


## 📂 Original Software Credits & Provenance
* **Author:** Marjan Šijanec (MS Software)
* **Year:** 1988
* **Original Platform:** Atari ST, GFA BASIC 3
* **Target Hardware:** Yamaha TX816 (8 x TF1 FM modules)
* **Original File Structures:** `c:\ym_tx816\ ... .vce` (voices), `.prf` (performances), `.rsc` (screen graphics)

---

## 📜 License
This historical reconstruction is shared for educational, archival, and preservation purposes, celebrating the legacy of early electronic music software development in the region.
