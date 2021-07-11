# Python Secrets
Curated list of all the hidden jokes, easter eggs and secrets in Python


## Table of Contents
- [Easter Eggs](#easter-eggs)
- [Command Line](#command-line)
- [Did you know?](#did-you-know)
- [Misc.](#misc)

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

### 4. InPynite?
```py
>>> hash(float('inf'))
314159
>>> hash(float('nan'))
0
```

### 5. Antigravity
```py
import antigravity
```

### 6. Random coordinates
```py
>>> from antigravity import geohash
>>> print(geohash(37.421542, -122.085589, b'2005-05-26-10458.68'))
# 37.857713 -122.544543
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

### 9. Not for the faint of heart
```py
>>> import types
>>> help(types.CodeType)                                          
```

## Command Line

### 1. CLI month calendar
```bash
python -m "calendar" 2021 7
``` 
For options: `python -m "calendar" --help`

## Did you know?

### 1. You can't subclass bool
```py
>>> class subclass_of_bool(bool):
...   pass
...
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: type 'bool' is not an acceptable base type
```

### 2. Oxford 15
```
>>> 0xfor-d
15
```

### 3. Unicode identifiers
```py
π = 3.1415
area = π * r ** 2
```

## Misc.

### 1. If statement without using an if
```py
# 1 condition
['cond1 is false', 'cond1 is true'][cond1]

# 2 conditions
['both false', 'cond1 is true', 'cond2 is true', 'both true'][2*cond2 + cond1]
```

### 2. For loop without using for, while
```py
def loop(array):
  if len(array) == 0:
    return 0
  else: 
    # do smth with array[0] for example print(array[0])
    print(array[0])
    return loop(array[1:])

loop([1,2,3,'a string'])
```
