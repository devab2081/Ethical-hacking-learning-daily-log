## Day 23 – IDOR Attack

Normal Flow:
User(ID:101) -> GET /profile?id=101 -> Server -> Profile(101)

Attack Flow:
User(ID:101) -> GET /profile?id=102 -> Server
Server checks DB for ID:102
Server does NOT check if User(101) owns ID(102)
Server -> Profile(102) -> DATA LEAK!
