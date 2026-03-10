# Project Axiom

**Phase 1 Prototype** of a geopolitical intelligence and simulation platform.

Project Axiom is a doctrine-aware geopolitical reasoning and simulation system designed to explore how states respond to crises under structured strategic assumptions. It combines:

- **Mandala** — event normalization, verification, and input pipeline
- **Chanakya** — country-specific strategic reasoning engines
- **Axiom** — multi-actor escalation simulation
- **Learning** — calibration, benchmark, and iteration loop
- **Command Center** — interactive dashboard for analysis and simulation

## Current Phase 1 Capabilities

- Country engines for:
  - India
  - Pakistan
  - China
  - United States
- Single-event strategic analysis
- Multi-actor crisis simulation
- Early calibration / benchmark testing
- Interactive dashboard prototype
- World map readiness visualization

## System Architecture

Raw Input / Live Event  
↓  
Mandala  
↓  
Chanakya  
↓  
Axiom  
↓  
Learning  
↓  
Command Center

## Core Layers

### Mandala
Mandala is the event pipeline and normalization layer. It is responsible for converting either analyst input or structured event data into machine-ready event objects.

### Chanakya
Chanakya is the strategic reasoning layer. It interprets crisis inputs using doctrine-aware country engines and produces response vectors such as:
- kinetic
- economic
- diplomatic
- domestic

### Axiom
Axiom is the simulation layer. It chains actor responses into turn-by-turn multi-actor crisis scenarios.

### Learning
Learning stores calibration logic, benchmark comparison, and iterative system refinement.

## Dashboard

The dashboard includes:
- **Command Center**
- **Mandala**
- **Chanakya**
- **Axiom**
- **Learning**

## Current Status

This repository is an early public prototype intended for portfolio, evaluation, and research demonstration purposes.

It is **not** presented as a deterministic predictor of real-world events.  
It is a structured geopolitical simulation and decision-support prototype.

## Local Run

### Install
`py -m pip install -r requirements.txt`

### Flask app
`py server.py`

### Streamlit dashboard
`py -m streamlit run streamlit_app.py`

### Simulator
`py simulator.py`

### Pakistan calibration tests
`py test_pakistan_calibration.py`

## Folder Structure

project_axiom/  
├── streamlit_app.py  
├── server.py  
├── simulator.py  
├── config.py  
├── learning.py  
├── state_matrix.py  
├── adversary_router.py  
├── test_pakistan_calibration.py  
├── requirements.txt  
├── countries.geo.json  
├── static/  
├── engines/  
│   ├── chanakya_india.py  
│   ├── chanakya_pakistan.py  
│   ├── pakistan_classifier.py  
│   ├── chanakya_china.py  
│   └── chanakya_us.py  

## Roadmap

### Phase 1
- Core country engines
- Early simulator
- Dashboard prototype
- Benchmark calibration

### Phase 2
- AI-assisted Mandala input interpreter
- Live event ingestion
- Broader country coverage
- Improved simulation workflows

### Phase 3
- Sector-specific reporting
- Hosted deployment
- Private analytical products
- Premium intelligence workflows

## Important Notice

This repository is published for portfolio, evaluation, and research demonstration purposes only.

**Copyright (c) 2026 Subin Sabu. All rights reserved.**

No permission is granted to copy, modify, redistribute, sublicense, deploy, or commercially use this code or derivative works without prior written permission.

## Author

SUBIN SABU

## Screenshots

dashboar view 1![FireShot Capture 016 - Project Axiom Command Center - localhost_page-0001](https://github.com/user-attachments/assets/641eb1b0-135e-47e7-8e1e-87721a950907)
dashboard view 2 ![FireShot Capture 015 - Project Axiom Command Center - localhost_page-0001](https://github.com/user-attachments/assets/7a0aab07-d857-4c95-89c6-1683df7d0dc4)

