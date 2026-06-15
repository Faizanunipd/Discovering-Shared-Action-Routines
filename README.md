# Discovering Shared-Action Routines

Source code and experimental artifacts accompanying the BPM 2026 paper:

**"Discovering Shared-Action Routines from Interleaved Executions for Robotic Process Automation"**

## Authors

- Massimiliano de Leoni, University of Padova
- Faizan Ahmed Khan, University of Padova



## Repository Structure

- gt_models/ : Ground truth models  
- ui_logs/ : Input UI logs  
- utils/ : Utility functions  
- out/ : Output results  
- Routine_Identification.py : Routine identification process  
- Routine_Evaluation.py : Evaluation of identified routines
- Statistical_Analysis_Results : Statistical significance analysis comparing the baseline approaches against our proposed technique (Community Detection with Label Splitting). The table reports the paired two-sided t-test statistic (t), the raw p-value (p), and the Holm-corrected p-value (p_H).  

---

## Requirements

Make sure Python 3 is installed.

---

## Setup Virtual Environment (Optional)

Create a virtual environment:

```bash
python3 -m venv venv
```

### Activate the environment

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

---

## Code Execution

Run the following scripts from the project root directory:

```bash
python Routine_Identification.py
```

```bash
python Routine_Evaluation.py
```

---

## Description

This repository provides an implementation of a technique to discover routine types with shared actions from interleaved executions in RPA logs. It includes datasets, ground truth models, and evaluation scripts to reproduce experimental results.

---

## Notes

- The virtual environment step is optional but recommended.  
- Ensure all required data files are present before execution.
