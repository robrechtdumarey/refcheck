# Refcheck: Patent Claim & Description Audit Tool

A high-precision logical engine for auditing the structural integrity and linguistic consistency of patent claims and their supporting descriptions.

## Features
- **Lineage Scoping:** Recursively tracks claim dependencies to ensure every feature reference has a valid antecedent.
- **Quad-Section Dashboard:**
  1. **Dependency & Feature Audit:** Visualized claim tree with syntax highlighting for introductions and references.
  2. **Feature Lifecycle Log:** Claims-only view of feature introductions and their usage history.
  3. **Claim-Description Alignment Map:** Automated cross-referencing between claims and description paragraphs.
  4. **Orphan Feature Audit:** Identifies features mentioned in the description with reference numbers that are missing from the claims.
- **Error Detection:** Automatically flags reference number mismatches, missing antecedents, and mentions without references.
- **Zero-Dependency:** Self-contained HTML/JS architecture with custom "Surgical Regex" logic.

## Usage
1. Paste your claim text into the "Claims Input" area.
2. Paste your description text (with `[xxxx]` paragraph markers) into the "Description Input" area.
3. Review the real-time audit results in the dashboard sections below.

## License
MIT License - Copyright (c) 2026 Robrecht Dumarey
