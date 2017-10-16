# pypong

* A simple ping library, pure python 3 implementation (Does not pipe commands to os terminal, does not require sudo/admin evelation)
* This is a simplified and tidied fork of pyping, which now works on py3. 
* Its not designed to work from CLI, like pyping does (I mean we have the real ping for that). Instead its designed to be used as a python module only. 
* Multiple pings and averaging is left as an excercise to the reader.

## Usage
```python
import pypong
pypong.ping("www.google.com")
pypong.ping("8.8.8.8")
```

## API
```ping(host, timeout=1)```

## Exceptions
```
HostUnreachable
ReplyTimeout
BadReply
HostLookupFailed
```
