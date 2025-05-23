# Work Breakdown Structure (WBS) - Baseball Monte Carlo Simulation

## 1. Project Initialization & Planning

- **1.1** Define primary objective: simulate baseball games using Monte Carlo methods.
- **1.2** Set up GitHub repository: `baseball-simulation-project`.
- **1.3** Establish initial directory structure:
  - `/functional_code/`
  - `/prepared_data/`
  - `/documentation_and_project_management_artifacts/`
  - `/results/`
- **1.4** Draft foundational project documents:
  - Functional Specifications
  - Work Breakdown Structure (WBS)
  - Product Backlog
  - Status Log
  - Activity List
  - Roadmap

---

## 2. Data Acquisition & Integration

- **2.1** Source and verify cleaned CSV files from external repository:
  - **2.1.1** Batting data: `cubs_standard_batting_clean.csv`, `whitesox_standard_batting_clean.csv`
  - **2.1.2** Pitching data: `cubs_standard_pitching_clean.csv`, `whitesox_standard_pitching_clean.csv`
- **2.2** Develop Python data-loading functions using `pandas`:
  - **2.2.1** Function for loading batting stats (AVG, OBP, SLG)
  - **2.2.2** Function for loading pitching stats (ERA)
  - **2.2.3** Add error handling and default fallback values for missing or malformed data

---

## 3. Simulation Engine Development

- **3.1** Define object-oriented components:
  - **3.1.1** `Player` class: includes name and batting stats
  - **3.1.2** `Pitcher` class: includes name and ERA
  - **3.1.3** `GameState` class: maintains inning, score, outs, and base runners
- **3.2** At-bat simulation logic:
  - **3.2.1** Implement probabilistic outcome generator using player and pitcher stats
- **3.3** Game flow logic:
  - **3.3.1** Simulate half-inning (stops after 3 outs)
  - **3.3.2** Simulate full 9-inning game (with optional early-ending rules)

---

## 4. Monte Carlo Simulation & Result Processing

- **4.1** Build loop for multiple game simulations (e.g., 10,000 iterations)
- **4.2** Aggregate results:
  - Count wins for each team
  - Optionally count ties (if included)
- **4.3** Compute win percentages
- **4.4** Export simulation results to:
  - Console
  - Visualization files (PNG charts)

---

## 5. Documentation & Project Finalization

- **5.1** Finalize all project documents (Functional Specs, WBS, etc.)
- **5.2** Ensure well-commented and readable Python code
- **5.3** Confirm all files are organized into appropriate directories:
  - Code in `/functional_code/`
  - Data in `/prepared_data/`
  - Visual outputs in `/results/`
- **5.4** Prepare submission deliverables:
  - Include GitHub repository link
  - Comment on use of AI (e.g., Gemini) in code and documentation drafting
- **5.5** Review for completeness and alignment with assignment criteria
