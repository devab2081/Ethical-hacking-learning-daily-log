## Day 21 – Upload Attack

User -> Uploads 'evil.php.jpg' -> Server
Server checks extension -> '.jpg' (Passes weak check)
File saved as 'evil.php' in /uploads/

Attacker -> Requests /uploads/evil.php -> Server executes PHP code! -> RCE
