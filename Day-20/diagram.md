## Day 20 – SOP & CORS

Origin A (site.com) -> Request -> Origin A (SAFE)

Origin A (site.com) -> Request -> Origin B (api.com)
Browser checks SOP -> Blocked!

Unless Origin B sends header:
Access-Control-Allow-Origin: site.com
Browser allows response
