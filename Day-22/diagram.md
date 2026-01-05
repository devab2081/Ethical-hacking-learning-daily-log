## Day 22 – Access Control

[User] -> Request /admin/deleteUser -> [Server]

Authorization Check:
1. Is user logged in? (Yes)
2. Is user Admin? (No)
   -> BLOCK REQUEST (403 Forbidden)

If check #2 is missing -> Vulnerability!
