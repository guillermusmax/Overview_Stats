<p>
  <img align="right" src="https://profile-counter.glitch.me/cypress0522/count.svg" />
  欢迎收听我的音乐~
</p>
<img align="right" src="https://github-readme-stats.vercel.app/api?username=cypress0522">

### class Meta(type):
```py
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)
```

### class Bio(metaclass=Meta):
```py
    name        : str = "Hsiang Nianian"
    designation : str = "Composer & AI Programmer"
    label       : str = "FragmentXwords"
    base        : str = "Zhejiang,China"
    blog        : str = "https://jyunko.cn"
```

### class Stack(metaclass=Meta):
```py
    languages   : Tuple[str, ...] = ("Python", "Lua", "HTML", "C++")
    databases   : Tuple[str, ...] = ("MySQL", "Mongo")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")
```

### class Social(metaclass=Meta):
```py
    Twitter     : str = "HsiangNianian"
    SoundCloud  : str = "hsiang_nianian"
    Spotify     : str = "Hsiang Nianian"
    Instagram   : str = "hsiang_nianian"
    Facebook    : str = "hsiang.nianian"
```
