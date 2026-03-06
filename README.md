# Python CI/CD Demo with GitHub Actions & Self-hosted Runner (macOS M1)

## Project Structure

- src/calculator.py: Main computation module
- tests/test_calculator.py: Unit tests for Calculator
- requirements.txt: Python dependencies
- .github/workflows/ci.yml: CI pipeline definition
- .gitignore: Ignore runner and cache files

## Quick Start

1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run tests locally:
   ```sh
   pytest tests/ -v
   ```
3. Push code to GitHub, pipeline will run automatically on self-hosted runner.

## Self-hosted Runner Setup
- See official GitHub docs or tutorial for macOS M1 runner installation.
