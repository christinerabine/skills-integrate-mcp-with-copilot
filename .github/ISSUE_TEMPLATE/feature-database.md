---
name: Persistent Database Storage
about: Add persistent database storage for users, activities, and uploads
labels: enhancement
---

title: "Feature: Persistent Database Storage"

## Problem
All data is currently in memory and lost on server restart.

## Solution
- Integrate a database (e.g., SQLite, MySQL, PostgreSQL)
- Store users, activities, and uploads persistently

## Acceptance Criteria
- Data persists across server restarts
- All features use the database for storage
