# 📌 MGIMT Campus Bulletin & Club Hub
### *A Responsive, Zero-JavaScript Academic Digital Notice Board*

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![No-JS](https://img.shields.io/badge/JavaScript-0%25%20(Pure%20CSS)-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Session-2026--27%20Active-success?style=for-the-badge)

**Department of Computer Science & Engineering**  
**MG Institute of Management and Technology (MGIMT), Banthra, Lucknow**  
*(Affiliated to Dr. A.P.J. Abdul Kalam Technical University, AKTU)*

</div>

---

## 🎯 Overview

The **MGIMT Campus Bulletin & Club Hub** is a lightweight, responsive digital notice board engineered to modernize departmental and extracurricular communication. It bridges the gap between physical pin-up corkboards and noisy messaging groups by providing structured, color-coded, and categorized digital notices.

A core engineering achievement of this project is its **Zero-JavaScript Architecture**: interactive category filtering, modal popup dialogs, and authentication flows are executed entirely through **semantic HTML5** and **declarative CSS3 logic**.

---

## ✨ Key Features

- ⚡ **Zero JavaScript Overhead:** Instantaneous rendering, minimal bandwidth consumption, and immune to client-side script vulnerabilities.
- 🏷️ **Pure CSS Category Filtering:** Filter notices across *All Pinned*, *Urgent*, *Academic*, and *Club Events* using the CSS `:checked` pseudo-class and General Sibling Combinators (`~`).
- 📜 **Non-Scripted Circular Modals:** In-depth circulars pop up seamlessly via the CSS `:target` pseudo-class with background blur overlays.
- 🔐 **Student & Faculty Gateway:** Dedicated authentication portal (`login.html`) with centered institutional branding and native HTML5 client-side validation.
- 📱 **Adaptive Multi-Device Layout:** Fluid responsive grid and flexbox structure optimized for smartphones, tablets, and desktop displays.

---

## 🏛️ Project Architecture

```text
mgimt-campus-bulletin/
│
├── index.html        # Main digital bulletin board with live corkboard grid & modals
├── login.html        # Authentication gateway with native HTML5 input validation
├── style.css         # Universal stylesheet (CSS Grid, Flexbox, :checked & :target hacks)
├── image.png         # Official MGIMT institutional emblem
└── README.md         # Detailed project overview and documentation
