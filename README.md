Fake Antivirus Simulation (Python)

A Python-based simulation that mimics the behavior of an antivirus product for educational and cybersecurity training. It demonstrates core concepts such as scanning directories, applying simple signature and heuristic checks, logging findings, and presenting a user-friendly report. The simulation is intended for classroom demos, red-team/blue-team exercises, and awareness training.

Important: this project is for learning and demonstration only. Do not use it to deceive or scare people, or to scan systems without explicit permission.

*Goals and Purpose*

Demonstrate how antivirus products present scan progress, apply signature and heuristic checks, and report results.
Provide a safe environment to teach defensive concepts: detection logic, false positives, logging, and incident response.
Offer a basis for building more advanced, non-destructive analysis tools (e.g., adding threat intelligence lookups, sandbox integration, or telemetry simulations).
This is a simulation — it intentionally avoids destructive features. The tool does not modify, delete, encrypt, or quarantine files. Findings are flagged for review only.

*Key Features*

Scans a single file or an entire directory (optionally recursive).
Signature-based checks using a configurable list of harmless signatures (filename patterns, sample strings, and test EICAR-like marker).
Heuristic checks that compute basic file metadata (size, entropy estimation optional) to demonstrate suspicious indicators.
Progress reporting and simulated scan speed to mimic user-visible behavior.
Detailed JSON/CSV report generation with timestamps and statistics.
Safe-by-default behavior: read-only, non-destructive, and includes explicit user confirmation before scanning.
Modular: detection rules are configurable and easily extended.
