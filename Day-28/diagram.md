## Day 28 – Defense in Depth

[Outer Wall] -> WAF (Web App Firewall)
  | A
  v
[Gate] -> Application Logic (Auth & Validation)
  | B
  v
[Inner Vault] -> Database (Least Privilege User)
  | C
  v
[Jewel] -> Encrypted Data

If Layer A fails, Layer B protects.
