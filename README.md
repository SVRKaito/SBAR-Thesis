# SBAR Tool for Nurses

A responsive, clinical-focused web application designed to streamline and improve nursing communication during patient handoffs. This tool implements the evidence-based **SBAR (Situation, Background, Assessment, Recommendation)** framework to ensure safer, structured, and more accurate documentation for healthcare professionals.

## 🚀 Features

* **Secure Authentication:** User registration (`signup.html`) and login interfaces equipped with modern UI standards (such as secure password strength visibility and toggle features).
* **SBAR Dashboard:** A dedicated interactive form (`SBAR.html`) for generating and reviewing structured clinical handoff reports.
* **Patient List Management:** Access to active records (`patientlist.html`) for monitoring assigned cases.
* **Research Utilization Framework:** Built-in section (`researchutil.html`) detailing the evidence-based principles and frameworks supporting the implementation of the SBAR dashboard in clinical practice.
* **Responsive & Responsive Design:** Completely styled from scratch (`.css` assets) ensuring seamless use on desktop monitors, tablets, and mobile smartphones at the bedside.
* **Iframe Breakout Security:** Scripts included to prevent the tool from being maliciously embedded inside external iframes.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid layouts, custom responsive breakpoints, custom-styled variables)
* **Scripting & Logic:** JavaScript (ES6+) for session management via `sessionStorage`/`localStorage` and dynamic DOM rendering.
* **Authentication/Backend integration ready:** Configured with handling blocks tailored for Firebase Auth services (error handling codes like `auth/email-already-in-use`, etc.).
