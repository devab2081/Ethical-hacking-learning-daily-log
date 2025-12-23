# Day 07 – SQL Injection (Visual Diagram)

## Normal Application Flow

```
User Input
|
v
Application
|
v
Database
|
v
Expected Result

```
---

## Vulnerable Logic (Concept Only)

```
User Input
|
v
Application (No Validation)
|
v
Database Query Modified
|
v
Unexpected Result

```
---

## Secure Logic

```
User Input
|
v
Validation & Secure Queries
|
v
Database
|
v
Safe Result

```
---

## Key Idea

```
Unsafe Input
|
v
Security Risk

Validated Input
|
v
Security Improved

```
