# livelogging-python

Structured live logging for Python. Use LiveComment for view logs.

```python
from livelog import LiveLog

llog = LiveLog(join("logdir", "llog.sh"))

llog.begin('Python-LLOG')

llog.put("Hello world")

llog.end()

```

## License
Code released under the MIT licence.
