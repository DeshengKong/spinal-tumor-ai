# spinal-tumor-ai
AI surgical decision framework for spinal tumors (IMSCT, IDEM, MSCC) with skill-based reasoning, intraoperative monitoring logic, and DTI-assisted planning.

## Overview

This repository implements a **skill-based AI surgical reasoning framework**
for intraspinal tumors.

The system models neurosurgical decision-making as modular skills that
handle:

• tumor classification  
• surgical strategy  
• intraoperative safety  
• uncertainty management

## Architecture

Router
├── Core Tumor Workflows
│   ├── IMSCT_management
│   ├── IDEM_management
│   └── conus_filum_tumor
│
├── Emergency Pathway
│   └── metastatic_spinal_cord_compression
│
├── Special Tumor Strategy
│   ├── hemangioblastoma_vascular_control
│   └── rare_intramedullary_pathology
│
├── Surgical Planning
│   └── spinal_DTI_tract_planning
│
├── Intraoperative Safety
│   └── IONM_rescue_decision
│
└── System Safety Layer
    └── uncertainty_triage
