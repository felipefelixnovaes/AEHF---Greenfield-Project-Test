# AEHF Greenfield Project Test

This repository is a greenfield pilot used to validate the **AI Engineering Harness Framework (AEHF)** on a very small real project.

## Pilot goal

Test whether AEHF helps a new project stay:
- clear
- lightweight
- reviewable
- easy for AI tools to understand
- less dependent on ad hoc prompting

## Project under test

A tiny task tracking web application with the minimum useful MVP scope:
- create task
- list tasks
- mark task as done
- in-memory persistence only

## Why this project exists

This is not intended to become a large product.
It exists to test whether AEHF improves greenfield delivery in practice.

## AEHF operating model in this repo

- `docs/` = durable project memory
- `specs/` = structured change packages
- `.github/copilot-instructions.md` = Copilot adapter entry point
- `CLAUDE.md` = Claude-style adapter entry point

## Initial pilot path

1. define the MVP clearly
2. capture minimum architecture and domain memory
3. create the first spec package
4. implement the smallest working app
5. review whether AEHF helped or created friction
6. record lessons learned
