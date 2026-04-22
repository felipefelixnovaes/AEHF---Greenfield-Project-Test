# Architecture Note

## Project type

Single small web application for task tracking.

## Initial architecture stance

Use the smallest understandable structure.
Avoid premature layering and avoid enterprise patterns unless the MVP proves they are needed.

## Expected MVP responsibilities

- store tasks in memory
- expose task creation
- expose task listing
- allow marking a task as done
- keep implementation simple enough for rapid review and iteration

## Current constraints

- no authentication
- no database
- no external integrations
- no microservices
- no complex infrastructure

## Architectural principle

Choose the smallest reliable design that keeps the code easy to understand for both humans and AI tools.
