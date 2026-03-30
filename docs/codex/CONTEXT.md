# CONTEXT.md

## Project Overview
This project implements one part of the Kanban board project. It implements the feature of creating various project columns, creating and dragging tasks within them, and rearranging tasks within the column.

## Goal
Learn to write a basic backend application using a new technology: TypeScript + NestJS + NodeJS

## Current Scope
- Project (column) creation
- Task creation (full CRUD)
- Drag and drop tasks across projects
- Drag and drop tasks within a project (priority change)

## Main entity
- tasks
- projects (columns)


## Out of Scope
- implement authentication/authorization
- create a bunch of users
- implement modules unrelated to the current feature

## Main Use Cases
- create a task (edit, delete)
- drag and drop a task across projects
- drag and drop a task within a project

## Technical Direction
- TypeScript 
- NestJS
- NodeJS
- PostgreSQL

## Current Open Questions
- application architecture is not defined

## Extra
- projects refers to columns with the project status (not started, in progress, closed), therefore, from now on it will be defined as a status column