## Day 25 – Sensitive Data Exposure

Date
05-01-2026

Topics Learned
Encryption in transit (HTTPS) vs at rest
Weak cryptographic algorithms (MD5, SHA1)
Hardcoded credentials in code
PII (Personally Identifiable Information) leaks

Tools / Platforms Used
Wireshark (Sniffing traffic)
Git leaks detection tools
SSL Labs

What I Learned Today
Sensitive data exposure happens when data is not properly protected.
Sending passwords over HTTP allows attackers to sniff them.
Storing passwords in plain text or with weak hashes allows them to be cracked.
Accidentally committing API keys to GitHub is a common form of exposure.
Always use strong encryption (TLS 1.2+, bcrypt/Argon2).

Key Takeaways
Use HTTPS everywhere
Hash passwords with salt
Never hardcode secrets
Classify data by sensitivity

Status
Completed
