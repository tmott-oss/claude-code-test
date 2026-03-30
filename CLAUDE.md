# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A browser-based Tic Tac Toe game delivered as a single self-contained HTML file (`tictactoe.html`). No build tools, dependencies, or server required — open the file directly in any browser.

## Running the Project

```bash
open tictactoe.html
```

## Architecture

Everything lives in `tictactoe.html`:

- **HTML** — 3x3 grid of `.cell` divs, a status line, scoreboard, and reset button
- **CSS** — dark theme (`#1a1a2e` background), grid layout, win-pulse animation
- **JS** — `board[]` array tracks state; `checkWinner()` tests all 8 win lines; click handler on each cell drives the game loop

## Git & GitHub

- Remote: `https://github.com/tmott-oss/claude-code-test`
- Commit style: imperative subject line, blank line, short body describing what and why
- Always commit and push after completing a feature or fix
