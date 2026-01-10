## Day 27 – Log Analysis

[Attacker] -> GET /admin.php -> [Server 404]
[Attacker] -> GET /login -> [Server 200]
[Attacker] -> POST /login (fail) -> [Server 403]
[Attacker] -> POST /login (fail) -> [Server 403]

[Log Monitor] -> Alerts: "Brute Force Detected"
