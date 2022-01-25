# The devGuide
This document covers new experimental features
### scon.FLAGS
#### Works with:
- `scon.dumps()`
- `scon.dump()`
- `scon.load()`
- `scon.loads()`

Add flags after the required parameters specified by the function.
#### Flags (`class scon.FLAGS`):
- `ONELINE`: removes newlines (**NOTE**: Only removes newlines that would normally be put into the file to make it human readable, If you have newline characters in your values, It will add newlines to the files.) (Only works on `dump()` or `dumps()`)
- `NO_VERIFY`: Skips file verification. (Only works on `load()` or `loads()`)