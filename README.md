# SimpleLogger

## Description

A simple logger I made for some projects a year ago.
Thanks to [CodeFix1027](https://github.com/CodeFix1027) for helping me release `v0.0.1.0`!

## Usage

```python
import logger

# Get a logging object.
log_obj = logger.LoggingObject(
    name='SampleLogger',
    logfile='logfile.log'
    )

# Set the log level to show.
log_obj.set_logging_level('NOTSET')

# Show logs in the screen.
log_obj.enable_logging()

log_obj.info("Sample Information message.")
log_obj.warning("Sample warning message.")
log_obj.error("Sample error message.")
log_obj.debug("Sample debug message.")
log_obj.critical("Sample critical message.")
```

## License

MIT License

Copyright (c) 2020 Chris1320

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
