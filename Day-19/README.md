## Day 19 – Cookies, Sessions, and Tokens

Date
30-12-2025

Topics Learned
What are Cookies?
Session ID management
JWT (JSON Web Tokens)
Session Hijacking risks

Tools / Platforms Used
Browser DevTools (Application Tab)
Burp Suite Sequencer
Cookie Editor extension

What I Learned Today
HTTP is stateless, so we use cookies to maintain sessions.
Session IDs are stored in cookies and validated on the server.
Tokens (like JWT) are self-contained and often used in APIs.
If a session ID is stolen, an attacker can impersonate the user.
Secure flags (HttpOnly, Secure) on cookies are important.

Key Takeaways
Don't expose sensitive data in cookies
Use HttpOnly to prevent XSS access
Rotate session IDs after login
JWTs must be signed securely

Status
Completed
