# Tasks Domain

## Purpose

Represent the smallest useful unit of work tracked by the application.

## Initial domain model

A task should have at least:
- identifier
- title
- completion status
- creation timestamp if needed by the implementation

## Core behaviors

- create a task
- list all tasks
- mark a task as done

## Out of scope for MVP

- authentication
- task categories
- due dates
- priorities
- persistence beyond memory
- collaboration

## Domain rule

For the pilot, a task is complete only when explicitly marked as done.
