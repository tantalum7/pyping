# pyping

* A simple ping library, pure python 3 implementation. Does not required sudo/admin evelation. 
* This is a simplified and tidied fork of pyping, which works on py3. 
* Its not designed to work from CLI, like pyping does (I mean we have the real ping for that). Instead its designed to be used as a python module only. 
* Multiple pings and averaging is left as an excercise to the reader.

```python
import pypong
pypong.ping("www.google.com")
```

ping(host, timeout=1)

