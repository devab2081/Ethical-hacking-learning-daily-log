## Day 25 – Data Protection

[Data in Transit]
Client --(Internet)-- Server
BAD: HTTP (Plaintext)
GOOD: HTTPS (Encrypted/TLS)

[Data at Rest]
Database:
BAD: Password="secret"
GOOD: Password=Hash(Salt + "secret")
