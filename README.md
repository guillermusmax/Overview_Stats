<p align="center"> 
  <img src="https://profile-counter.glitch.me/cypress0522/count.svg" />
</p>

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Hsiang Nianian"
    designation : str = "Composer & AI Programmer"
    Label       : str = "FragmentXwords"
    base        : str = "Zhejiang,China"
    blog        : str = "cypress0522.github.io"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Lua", "HTML", "C++")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")


class Social(metaclass=Meta):
    Twitter     : str = "Hsiang_Nianian"
    SoundCloud  : str = "hsiang_nianian"
    Spotify     : str = "Hsiang Nianian"
    Instagram   : str = "hsiang_nianian"
    Facebook    : str = "hsiang.nianian"
    
```
