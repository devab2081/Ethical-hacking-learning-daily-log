## Day 23 – Insecure Direct Object References (IDOR)

Date
03-01-2026

Topics Learned
What is IDOR?
How IDOR leads to data leaks
Predictable Resource IDs
Testing for IDOR

Tools / Platforms Used
Burp Suite (Parameter modification)
Postman
Custom vulnerable app

What I Learned Today
IDOR occurs when an application exposes a reference to an internal object (like a file or database key) without access control checks.
Simply changing the ID in the URL (e.g., /user/101 -> /user/102) can expose another user's data.
It is a type of Broken Access Control but specific to object references.
Prevention involves checking permissions every time an object is accessed.

Key Takeaways
IDs should not be predictable (use UUIDs)
Always verify ownership of the object before serving it
Don't rely on the user knowing the ID for security

Status
Completed
