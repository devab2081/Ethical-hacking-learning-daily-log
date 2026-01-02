# Day 19 – Cookies, Sessions, and Tokens (Visual Diagram)

## Cookie-Based Flow
```
User Browser
|
| Cookie
v
Web Server

```
---

## Session-Based Flow

```
User Login
|
v
Session Created (Server)
|
v
Session ID Stored (Browser)
|
v
User Requests

```
---

## Token-Based Flow
```

User Login
|
v
Token Issued
|
v
Token Sent with Requests
|
v
Server Verifies Token

```
