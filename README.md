### Fork of https://github.com/Artucuno/Compasspy as it no longer works.
# Compasspy
Simplest and probably only *working* Python Package to scrape compass.education

## Installation
```
pip install -U git+https://github.com/Jake4353/Compasspy-Cloudflare
```  
## Simple Example
```py
from compasspy.client import Compass
                  # school domain is the "ExampleSchool".compass.education
client = Compass('<School Subdomain>', '<Authentication Cookie>')
client.login()
```
[More Examples](/examples) | [How to get Authentication Cookie](/examples/cookie.md)
