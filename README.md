# Saha+ – Interactive Digital Health Platform

## Overview
This project was developed as part of the **PW – 2nd Year Engineering Program** at **Esprit School of Engineering** (Academic Year 2026–2027).

Saha+ is an all-in-one digital health platform that connects health literacy, healthcare accessibility, asynchronous mental-health support and safe AI guidance into a single patient journey, centered around an interactive human body.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Contributors](#contributors)
- [Academic Context](#academic-context)
- [Getting Started](#getting-started)
- [Acknowledgments](#acknowledgments)

## Features
- **Interactive Human Body Atlas** – click an organ to see its function, key vitals, common symptoms, prevention tips and red flags.
- **Medical Map & Blood Donation Network** – hospitals, doctors filtered by specialty, blood donation centers, blood-type compatibility matrix and eligibility check.
- **Mental Health SafeSpace** – video, privacy-blur or voice-only recordings sent to a therapist for asynchronous follow-up, with an emotion timeline.
- **Guardrailed AI Health Assistant** – curated answers from reliable sources with 3-tier triage (informational / consult a professional / urgent).

## Tech Stack
### Frontend
- HTML5, CSS3, JavaScript
- Bootstrap (Front Office template)
- Admin dashboard template (Back Office)

### Backend
- PHP (MVC architecture)
- MySQL

## Architecture
```
├── app/
│   ├── Controllers/   # handle requests, call models, choose views
│   ├── Models/        # data classes
│   └── Views/         # pages (front office & back office)
│       └── partials/  # shared parts: head, navbar/sidebar, footer, scripts
├── assets/            # css, js, images
└── index.php          # entry point / router
```

## Contributors
- Ibrahim Kbaier
- Rayen Mediouni
- Mohammed Amdouni
- Marame Azizi
- Mohamed Rached Lakhel

## Academic Context
Developed at **Esprit School of Engineering – Tunisia**
PW – 2A8 | 2026–2027

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/DJPAA-IB/Esprit-PW-2A8-2027-SahaPlus.git
   ```
2. Move the folder into `htdocs` (XAMPP) or `www` (WAMP).
3. Start Apache and MySQL from the XAMPP control panel.
4. Open in your browser:
   ```
   http://localhost/Esprit-PW-2A8-2027-SahaPlus/
   ```

## Acknowledgments
- Our tutors at **Esprit School of Engineering**
- Template authors (ThemeWagon / TailAdmin)

> ⚠️ **Disclaimer:** Saha+ is an educational project. It does not replace medical professionals, diagnose conditions, or prescribe treatments.
