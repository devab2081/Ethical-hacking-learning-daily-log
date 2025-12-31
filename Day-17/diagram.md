## Day 17 – Input Validation Flow

User Input -> [Validation Layer] -> [Sanitization Layer] -> [Database]

[Validation Layer]
Type Check (Int, String)
Format Check (Email, Phone)
Length Check

[Sanitization Layer]
Escape HTML entities
Remove SQL keywords
Encode output

Result: Safe Data
