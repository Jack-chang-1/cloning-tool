# 🧬 Seamless Cloning Design Tool

![Version](https://img.shields.io/badge/Version-V1.0-blue) ![Author](https://img.shields.io/badge/Author-Cinda-purple) ![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Introduction

**Seamless Cloning Design Tool** is a lightweight, web-based utility designed for molecular biologists. It simplifies the workflow for **Multi-Fragment Homologous Recombination** (compatible with **Gibson Assembly**, **In-Fusion**, **NEBuilder**, etc.).

This tool integrates **Primer Design**, **Plasmid Map Visualization**, and a **Reaction Mixture Calculator** into a single interface. No installation is required—just open it in your browser.

🔗 **Live Demo**: [Click here to use the tool](https://jack-chang-1.github.io/cloning-tool/) 

---

## ✨ Key Features

* **⚡️ Smart Primer Design**:
    * Supports designing primers for up to **14 fragments** simultaneously.
    * Automatic **Tm calculation** (based on the Nearest-Neighbor thermodynamic model).
    * One-click **CSV Export** for easy primer ordering.
* **✂️ Vector Linearization Assistant**:
    * Built-in library of common Restriction Enzymes.
    * Supports **Circular Sequence Input**: Automatically handles restriction sites spanning the sequence start/end.
    * Auto-extraction of Upstream (5') and Downstream (3') homology arms.
* **🗺️ Interactive Visualization**:
    * Generates a real-time **Circular Plasmid Map**.
    * Visualizes the ratio between the vector backbone and insert fragments.
* **🧪 Reaction Mixture Calculator**:
    * Calculate the required volume of each fragment based on measured concentrations (ng/μL).
    * Customizable **Molar Ratios** (e.g., Vector:Insert = 1:2) and total reaction volume.
* **🔒 Data Privacy**:
    * **Client-Side Only**: All calculations are performed locally in your browser.
    * **No Cloud Upload**: Your sequences are never sent to a server, ensuring your data remains secure.

---

## 🚀 User Guide

### Step 1: Vector Preparation
You can define your linearized vector in two ways:

1.  **Auto-Digestion Mode**:
    * Paste the full plasmid sequence.
    * Select the **5' Enzyme** and **3' Enzyme** from the dropdown menu.
    * Click **"Digestion Simulation"** (执行酶切) to auto-fill the ends.
2.  **Manual Input Mode**:
    * Directly paste the sequence into the **"Upstream Sequence (5')"** and **"Downstream Sequence (3')"** text areas.

### Step 2: Insert Fragments
* Click the `+ Add Fragment` button.
* Paste your fragment sequences (5' to 3') in the order of assembly.
* The tool automatically filters out non-ATCG characters.

### Step 3: Configuration & Run
* Set parameters like **Homologous Arm Length** (Default: 20bp) and **Target Tm**.
* Click **"Generate Primers"** (开始批量设计引物).

### Step 4: Results & Export
* Review the generated primer list and the circular plasmid map.
* Click **"📊 Export CSV"** to download the primer list.

### Step 5: Reaction Setup
* Scroll down to the **"Reaction Mixture Calculator"**.
* Input the **Concentration (ng/μL)** for your vector and purified fragments.
* Set your desired **Molar Ratio** and **Total Volume**.
* Click **"Calculate"** to get the pipetting volumes.

---

## 💻 Offline / Local Usage

If you need to use this tool without an internet connection:

1.  Download the `index.html` file from this repository.
2.  Open the file directly in any modern web browser (Chrome, Edge, Safari, Firefox).

---

## 🤝 Feedback & Contribution

If you encounter any bugs or have suggestions for new features, please feel free to open an Issue or contact the author.

**Author:** Cinda  
**Version:** V1.0 (2026-01-15)

---
*Developed for efficient cloning.* 🧬
