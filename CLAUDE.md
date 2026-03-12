# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Git workflow

Commit and push to GitHub continuously as work progresses — after every meaningful unit of work (new feature, bug fix, significant edit). Never leave changes uncommitted. This ensures the project history is always recoverable and nothing is lost.

- Remote: `origin` → https://github.com/rjasur99-ctrl/Claudetest
- Branch: `master`
- After each meaningful change: `git add <files>`, write a clean descriptive commit message, then `git push`
- Commit messages should describe *what* changed and *why*, not just "update file"
- Do not batch unrelated changes into a single commit — keep commits focused

## Project structure

This is a collection of browser-based games and experiments — plain HTML/CSS/JS files, no build step, no framework, no package manager. Each game is a single self-contained `.html` file that can be opened directly in a browser.

## Running locally

Open any `.html` file directly in a browser. No server required.
