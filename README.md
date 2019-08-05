### sortedcontainers
---
https://github.com/grantjenks/python-sortedcontainers/

http://www.grantjenks.com/docs/sortedcontainers/

```py
import sortedcontainers
help(sortedcontainers)
from sortedcontainers import SortedDict
help(SortedDict)
help(SortedDict.popitem)


from sortedcontainers import SortedList
sl = SortedList(['e', 'a', 'c', 'd', 'b'])
sl
sl *= 10_000_000
sl.count('c')
sl[-3:]
from sortedcontainers import SortedDict
sd = SortedDict({'c': 3, 'a': 1, 'b': 2})
sd
sd.popitem(index=-1)
from sortedcontainers import SortedSet
ss = SortedSet('abracadabra')
ss
ss.bisect_left('c')
```

```sh
pip install sortedcontainers
```

```
```


