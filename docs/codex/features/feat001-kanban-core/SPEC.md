# SPEC.md

## Feature Name
feat001-kanban-core

## Overview
Implement the core Kanban backend feature:
- create status columns
- create and manage tasks
- move tasks across columns
- reorder tasks within a column

## Goal
Build a minimal but working backend feature for a Kanban board and use it to learn NestJS + TypeScript + NodeJS in practice.

## In Scope
- create status columns
- create tasks
- update tasks
- delete tasks
- move tasks across columns
- reorder tasks within a column
- get board state for current feature

## Out of Scope
- authentication / authorization
- users and roles
- comments
- labels
- attachments
- notifications
- any unrelated modules

## Main Use Cases
- create a status column
- create a task
- edit a task
- delete a task
- drag and drop a task to another status column
- drag and drop a task inside the same status column

## Core Rules
- tasks belong to a single status column
- tasks must keep a stable order inside a status column
- moving a task must keep ordering valid
- implementation should stay simple and readable

## Acceptance Criteria
- status columns can be created
- tasks support basic CRUD
- tasks can be moved across status columns
- tasks can be reordered within a status column
- board state can be retrieved
- invalid actions are handled predictably
- feature works locally and can be checked manually