# Python Secrets
Curated list of all the hidden jokes, easter eggs and secrets in Python


## Table of Contents
- [Easter Eggs](#easter-eggs)
- [Command Line](#command-line)


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

### 10. Among Us SUS?
AMONG 😳 US 🅱️ IN 😱 REAL 😵 LIFE 💩 SUS 📮 SUS
AMONG 😳 US 🅱️ IN 😱 REAL 😵 LIFE 💩 SUS 📮 SUS
PLAYING 🐈 AMONG 💀 US 😡 IN 🤗 REAL 🤠 LIFE
SPACESHIP 🚀 WITH 👾 MY 👅 CREW
GOTTA 🥷🏿 SPLIT 😚 UP 🤡 SPREAD ⁉️ OUT 📮CUZ 😃 WE 😋 ALL 😐 GOT 😯 TASKS 👻 TO 👽 DO
GOTTA 👿 FIND 👺 THE 🤧 IMPOSTER 🤫 AS 👀 THEY 🛖 TRY 🗿 TO 🛶 SA🅱️OTAGE
WHO 📮CAN 🅱️ WE 🇫🇷 TRUST 😂 IN 🤪 THIS 🤯 AMONG 🤭 US 🤣 ENTOURAGE.

## Command Line

### 1. CLI month calendar
```bash
python -m "calendar" 2021 7
``` 
For options: `python -m "calendar" --help`



