## Day 21 – File Upload & Download Security

Date
01-01-2026

Topics Learned
Risks of unrestricted file uploads
Web shell execution
MIME type validation bypass
Path Traversal in downloads

Tools / Platforms Used
DVWA (File Upload)
Burp Suite (Intercept upload)
PHP Web Shells

What I Learned Today
File upload features are critical attack vectors if not secured.
Attackers can upload malicious scripts (webshells) to gain control of the server.
Only checking the file extension or Content-Type header on the client side is insufficient.
Files should be renamed, stored outside the web root, and scanned for malware.

Key Takeaways
Don't trust file extensions
Store uploads outside web root
Rename uploaded files randomly
Validate file content (magic bytes)

Status
Completed
