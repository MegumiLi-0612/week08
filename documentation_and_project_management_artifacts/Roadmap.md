# Product Roadmap: Baseball Monte Carlo Simulation

## Phase 1: Core Simulation Development (Completed ~May 20, 2025)

### M1.1: Core Game Mechanics
- Define class structures: `Player`, `Pitcher`, and `GameState`.
- Implement probabilistic logic for individual at-bats.
- Simulate half-innings (3-out logic).
- Simulate full 9-inning games with inning and score tracking.
- Maintain basic game state (outs, inning, base runners, score).

### M1.2: Data Integration from CSV
- Load batter stats (BA, OBP, SLG) from external CSV files.
- Load pitcher stats (ERA) from CSV.
- Include fallback defaults for missing or malformed data.

---

## Phase 2: Monte Carlo Engine & Output (Completed ~May 21, 2025)

### M2.1: Simulation Loop
- Implement batch processing of multiple games (e.g., 1000 simulations).
- Accumulate and store win/loss records per team.

### M2.2: Result Reporting
- Calculate and print win percentages for each team.
- (Optional) Display average runs per game for each side.

---

## Phase 3: Documentation & Repository Finalization (Due by Assignment Deadline)

### M3.1: Documentation
- Finalize core documents:
  - Functional Specifications
  - Work Breakdown Structure
  - Product Backlog
  - Status Log
  - Activity List
  - Roadmap (this file)

### M3.2: Code-Level Improvements
- Add descriptive comments and docstrings to Python code.

### M3.3: Repo Structure & Compliance
- Organize files into appropriate directories per project guidelines.
- Ensure root `README.md` provides clear setup and usage instructions.

### M3.4: Assignment Submission
- Include notes on AI-assisted development and peer feedback.
- Review and verify all deliverables are present and functional.

---

## Future Enhancements (Beyond Current Scope)

- **FEAT-001:** Add advanced hitting stats (e.g., K%, BB%, ISO) for more nuanced at-bat outcomes.
- **FEAT-002:** Implement realistic base-running logic and scoring scenarios.
- **FEAT-003:** Introduce pitcher fatigue and bullpen substitution mechanics.
- **FEAT-004:** Include differentiated out types (e.g., flyouts, groundouts) based on hitter profiles.
- **FEAT-005:** Build a simple user interface for input and result display.
- **FEAT-006:** Integrate fielding stats and defensive effects into simulations.
- **FEAT-007:** Enable simulation of full seasons using a dynamic game schedule.

