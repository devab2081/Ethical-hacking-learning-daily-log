## Day 20 – Same-Origin Policy & CORS Basics

Date
31-12-2025

Topics Learned
Same-Origin Policy (SOP) definition
Cross-Origin Resource Sharing (CORS)
Preflight requests (OPTIONS)
Relaxing SOP safely

Tools / Platforms Used
Browser Console
Test CORS sites
Burp Suite

What I Learned Today
SOP prevents scripts on one origin from accessing data on another.
Origin = Protocol + Domain + Port.
CORS allows servers to specify who can access their resources.
Misconfigured CORS (Access-Control-Allow-Origin: *) can be dangerous if credentials are allowed.
Preflight requests check if the actual request is safe to send.

Key Takeaways
SOP is a fundamental browser security mechanism
CORS relaxes SOP
Be careful with 'Access-Control-Allow-Origin: *'
Start with restrictive policies

Status
Completed
