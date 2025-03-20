# Secure Code Game
## Welcome to Secure Code Game - Season 1! 👋
To get started, please follow the 🛠️ [set up guide](#setup-guide) (if you haven't already).
Refer to the [Hints](#hints) for helpful information and [Tasks](#time-to-start) to head to the challenge directly.

## Overview
This program validates transactions in systems where orders consist of multiple items and payments. It ensures that the financial records are consistent and highlights any discrepancies.

## 📝 Storyline
A few days before the massive shopping event Cyber Monday, an electronics shop without an online presence rushed to create a website to reach a broader customer base. As a result, they spent all their budget on development without investing in security. Do you have what it takes to fix the bug and progress to Level 2?

## ⌨️ What's in the repo?
For each level, you will find the same file structure:
- `src/` includes the vulnerable code to be reviewed.
- `tests/` contains the unit tests that should still pass after you have implemented your fix.

## 🚦 Time to start!
- [ ] Observe the **Github Workflow** logs, and identify the failing test cases.
- [ ] Open a new **Github Issue** to address the problem and your observations.
- [ ] Create a new **Git Branch** and work on the fix.
    1. Review the code in `src/main.py`. Can you spot the bug(s)?
    2. Try to fix the bug(s). Ensure that unit tests are still passing 🟢.
- [ ] Make a new **Pull Request** with a description of what you fixed.
- [ ] Observer the GitHub Workflow logs, and ensure that the code is error free.
- [ ] Once all workflow pass, **merge** the pull request.

> [!NOTE]
> You successfully completed the level when the Github Workflow passes 🟢.

## 💡 Hints
The program currently has vulnerabilities related to floating-point arithmetic. Pay close attention to how decimal values are handled during transaction validation.

<!-- Additional hints will be provided if needed -->

# Setup Guide
## Local Installation
```bash
git clone https://github.com/kgchinthana/secure-code-game.git
cd secure-code-game
pip install -r requirements.txt
```

## Usage
```bash
python src/main.py [arguments]
```

## Running Tests
```bash
python -m pytest
```
