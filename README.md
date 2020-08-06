#### Http Status Codes

List of most available http status codes written in Python.

#### Usage

```python
    >>> from app import codes
    >>> 428  Precondition Required
    >>> 429  Too Many Requests
    >>> 400  Bad Request
    >>> ...
    >>> codes[200]
    >>> codes[304]
    >>> codes[404]
    >>> codes[502]
    >>> ...
    >>> does_status_code_exist(404)
    >>> Yes, the status code 404 exists 😀
    >>> ...
    >>> does_status_code_exist(150)
    >>> ...
```