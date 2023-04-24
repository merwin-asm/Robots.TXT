# Robots.txt Parser

Robots.txt parser for python.
Better than the OG one for some reasons.


## What advantages you will have using this instead of OG 'urllib.robotparser' ?

-  Supports the use of full url / any url rel to the site
-  Supports proxies
-  Does show dissallowed sites

##  Use :

```
import robots_txt

res = disallowed("https://www.google.com/blablabla", proxy=None) 
# returns the disallowed sites for google.com
```
