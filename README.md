# Grade Calculator

A browser-based grade calculator for computing a final grade from weighted components, with a semester-organised average grade tracker.

## Features

### Grade Calculator
- Add any number of grading components (e.g. written exam, portfolio, oral exam)
- Set grades per component using a slider or dropdown (A–F)
- Adjust weights per component using sliders or number inputs — always sums to 100%
- Lock individual component weights to exclude them from auto-redistribution
- Displays the calculated final grade with weighted score and description
- Combination table for all possible outcomes (shown when exactly 2 components are active)
- Add the result directly to the average grade tracker

### Average Grade Tracker
- Manually add courses with a name and grade
- Organise courses into semesters
- Drag and drop to reorder courses within or between semesters
- Rename, collapse, and remove semesters
- Per-semester average grade displayed in the header
- Overall average grade across all semesters

## Usage

Open `index.html` directly in a browser — no installation or server required.

1. Set your grading components and adjust their weights
2. Select a grade for each component
3. Click **+ Add** to save the result to a semester in the tracker
4. Use **+ Add manually** to add courses without going through the calculator
5. Switch between semesters using the semester picker or by clicking a semester header

## Grade Scale

| Grade | Description              |
|-------|--------------------------|
| A (6) | Excellent performance    |
| B (5) | Very good performance    |
| C (4) | Good performance         |
| D (3) | Satisfactory performance |
| E (2) | Sufficient performance   |
| F (1) | Fail                     |

## Technical

Pure HTML/CSS/JavaScript — single file, no dependencies, no build step.