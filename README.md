# H<sub>ttp</sub> H<sub>eaders</sub>
The enumeration which contains all headers constants from RFC1945, RFC2518, RFC2616.

# Usage
```python
import requests 
from hh import H  # - is a short alias for HttpHeaders

requests.get('https://yandex.com', headers={H.CONTENT_TYPE: "text/html"})
```
