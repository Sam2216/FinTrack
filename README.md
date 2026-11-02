# FinTrack

FinTrack is a planned Java command-line application for tracking income and expenses, setting monthly spending limits, and monitoring remaining funds. I’m building it to improve my spending habits and make budgeting easier.

## MVP Scope

- Set and update a monthly budget.
- Record expenses with an amount, date, and category.
- Record income separately from the spending budget.
- Display monthly income, total expenses, and remaining budget.
- Show a warning when spending exceeds the budget.
- Save and reload records between program sessions.

Recording income will not automatically increase the spending budget. Users will decide whether to adjust their limit.

## Future Plans

- Set savings goals and track progress.
- Add category-specific spending limits.
- Compare spending across months.
- Edit or delete existing transactions.

## Tech Stack

- **Language:** Java
- **Interface:** Terminal menu using `Scanner`
- **Money calculations:** `BigDecimal`
- **Dates:** `java.time`
- **File storage:** `java.nio.file`
- **Currency formatting:** `NumberFormat`
- **Data format:** Local tab-separated text files
- **Version control:** Git and GitHub

No external APIs or third-party libraries are required for the MVP.

## Project Structure

- `src/` — Java source code will go here.
- `docs/` — Eisenhower Matrix and system diagram files.
- `.gitignore` — Rules for excluding generated files and personal data.

## Development Plan

1. Set up the repository and project folders.
2. Create the terminal menu.
3. Implement monthly budget creation and updates.
4. Add expense recording.
5. Add income recording.
6. Build the monthly summary and over-budget warning.
7. Implement saving and loading records.
8. Check the complete workflow and update documentation.

## Design Documents

- [Eisenhower Matrix](docs/eisenhower-matrix.md)

The system diagram image and editable source will be added to `docs/` after completion.

## Project Status

Planning stage. Implementation will follow the development milestones above.

## Personal Data

Real financial records will stay out of this public repository. Examples and demonstrations will use fictional data.s public repository. Examples and demonstrations will use fictional data.
