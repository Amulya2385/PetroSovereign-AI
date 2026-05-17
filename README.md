# PetroSovereign AI

## Fuel Survival Intelligence for Crisis-Resilient Petrol Bunk Operations

PetroSovereign AI is a research-grade artificial intelligence project that develops a multi-engine decision intelligence pipeline for petrol bunk fuel crisis operations.

The project focuses on estimating fuel survival, detecting crisis signals, identifying operational risks, and generating command-level recommendations during shortage-like conditions. It is designed as a structured AI decision-engine prototype that can support future research, dashboard development, and real-world system extension.


## Repository Purpose

This repository contains the complete project notebook and documentation for PetroSovereign AI.

The repository is intended to present the project in a clean, review-ready format for:

- academic evaluation
- research review
- technical portfolio presentation
- AI/ML project demonstration
- future product or dashboard extension

The notebook includes the full pipeline from crisis simulation to final command intelligence and validation outputs.

## Core Research Idea

The central idea of PetroSovereign AI is to treat petrol bunk fuel availability as a **survival intelligence problem**.

Instead of only tracking current stock, the system estimates how long available fuel can sustain operations under abnormal demand, tanker delay, hoarding behaviour, queue pressure, emergency reserve stress, and possible fuel loss conditions.

This allows the system to move from simple monitoring toward operational decision intelligence.


## Key Capabilities

PetroSovereign AI provides the following capabilities:

- fuel survival estimation
- worst-case survival assessment
- demand surge risk detection
- panic regime detection
- tanker delay risk prediction
- hoarding risk detection
- fuel loss and pilferage audit intelligence
- crisis severity scoring
- active risk channel identification
- final command state classification
- administrative action recommendation
- dashboard-ready output generation
- validation and audit reporting


## System Architecture

The project is structured as a multi-engine intelligence pipeline.

| Engine | Intelligence Layer |
|---|---|
| Engine 1 | Fuel survival estimation |
| Engine 2 | Panic regime detection |
| Engine 3 | Replenishment priority intelligence |
| Engine 4 | Crisis severity scoring |
| Engine 5 | Demand surge risk detection |
| Engine 6 | Tanker delay risk prediction |
| Engine 7 | Hoarding risk detection |
| Engine 8 | Fuel loss audit intelligence |
| Engine 9 | Final crisis command intelligence |
| Engine 10 | Dashboard-ready intelligence layer |
| Engine 11 | Research validation and audit layer |

Each engine produces a specific operational signal. These signals are combined into a final command intelligence layer that generates risk scores, command states, alert levels, and recommended actions.


## Pipeline Overview

```text
Digital Twin Crisis Simulation
        ↓
Feature Engineering
        ↓
Engine-wise Intelligence Layers
        ↓
Machine Learning and Rule-based Risk Detection
        ↓
Final Command Intelligence
        ↓
Dashboard-ready Outputs
        ↓
Validation, Leakage Checks, and Audit Packaging
```


## Methodology Summary

The project uses a controlled digital twin simulation because complete real-world petrol bunk crisis datasets are not publicly available in a structured format.

The simulation creates realistic operating scenarios such as:

- normal demand periods
- demand surge
- panic-like buying behaviour
- tanker delay
- queue pressure
- hoarding behaviour
- emergency reserve pressure
- abnormal fuel loss
- compound crisis states

The simulation is used to test whether the decision pipeline can detect, combine, and interpret multiple crisis signals in a controlled environment.

The objective is not to claim real-world deployment accuracy from simulated data. Instead, the simulation provides a controlled experimental environment for designing and validating the AI decision logic.


## Machine Learning Approach

The project uses a hybrid intelligence approach:

1. **Machine learning models** for predictive risk detection.
2. **Rule-based logic** for operational thresholds, alert levels, and command interpretation.
3. **Validation checks** to ensure model inputs and dashboard outputs remain clean and aligned.

Forecasting and estimation layers are evaluated using regression-oriented metrics where applicable.

Risk detection engines are evaluated using classification metrics such as:

- accuracy
- precision
- recall
- F1-score

The project avoids relying on one misleading overall accuracy score. Instead, each engine is evaluated according to its specific task, output type, and operational role in the final command intelligence pipeline.


## Final Command Intelligence

The final command intelligence layer combines multiple risk signals into a unified operational view.

It generates:

- command risk score
- command state
- active risk channel count
- final administrative action
- demand surge action
- tanker delay action
- hoarding action
- fuel loss audit action
- final command recommendation

This layer is designed to support decision-making during fuel shortage or crisis-like operating conditions.


## Dashboard-ready Outputs

The project prepares structured outputs that can be used for dashboard development.

Final outputs include:

- final command intelligence table
- dashboard master dataset
- executive KPI cards
- command risk time-series
- command state distribution
- active risk channel distribution
- engine-wise alert overlap summary
- emergency timestamp records
- validation summary
- audit export manifest

These outputs are suitable for future visualization in tools such as Power BI, Tableau, Streamlit, Dash, or a custom web dashboard.


## Validation and Audit Layer

The final validation layer checks the integrity of the project outputs.

It verifies that:

- clean feature sets are available
- leakage-sensitive model input features are removed
- dashboard outputs do not expose harmful sensitive columns
- Engine 9 and Engine 10 outputs are aligned
- final audit-ready files are exported successfully

This layer improves the reliability, transparency, and review quality of the project.

## Repository Structure

```text
PetroSovereign-AI/
│
├── PetroSovereign_AI_Fuel_Survival_Intelligence.ipynb
├── README.md
```

## How to Use

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells sequentially from top to bottom.
3. Review the engine-wise outputs and validation summaries.
4. Use the generated final tables for dashboard creation or further analysis.


## Expected Outputs

After successful execution, the project generates final datasets such as:

```text
engine9_final_command_intelligence.csv
engine10_dashboard_master.csv
engine10_executive_kpi_cards.csv
engine11_final_validation_summary.csv
engine11_project_validation_status.csv
engine11_clean_feature_rescan.csv
engine11_dashboard_output_safety_scan.csv
```

These files represent the final command, dashboard, and validation layers of the project.


## Current Project Status

The current version includes:

- digital twin simulation
- engine-wise intelligence pipeline
- machine learning based risk detection
- final command intelligence generation
- dashboard-ready output preparation
- clean retraining validation
- leakage and output safety checks
- final audit export package


## Future Scope

Future versions of PetroSovereign AI can be extended with:

- real petrol bunk POS integration
- tank sensor and IoT telemetry
- tanker GPS data
- supplier reliability feeds
- CCTV-based queue estimation
- live dashboard deployment
- backend APIs
- database integration
- cloud deployment
- district-level fuel crisis monitoring
- field validation using real operational data


## Important Note

This project uses simulated crisis data for controlled experimentation and decision-engine validation because complete real-world petrol bunk crisis datasets are not publicly available in a structured format.

The current version is a research-grade AI decision-engine prototype. It is not a deployed production system and should not be used for real-world operational decisions without real data integration, field validation, and domain expert review.
