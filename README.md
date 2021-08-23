# Python Secrets
Curated list of all the hidden jokes, easter eggs, secrets and the lesser known things in Python


## Table of Contents
- [Did you know?](#did-you-know)
- [Easter Eggs](#easter-eggs)


## Easter Eggs

### 1. Zen of Python
```py
import this
```

### 2. Easiest Hello World
```py
import __hello__
```

### 3. Braces in python?
```py
from __future__ import braces
  File "<stdin>", line 1
SyntaxError: not a chance
```

### 5. Antigravity
```py
import antigravity
```

### 7. Friendly Language Uncle For Life
```py
>>> from __future__ import barry_as_FLUFL
>>> 1 != 3
  File "<stdin>", line 1
    1 != 3
       ^
SyntaxError: with Barry as BDFL, use '<>' instead of '!='
>>> 1 <> 3
True
```

### 8. New parser?
```py
>>> __peg_parser__
  File "<stdin>", line 1
    __peg_parser__
    ^
SyntaxError: You found it!
```
Note: This will work only in 3.9 and will be removed in 3.10 along with the LL(1) parser with the introduction of the new PEG parser.
