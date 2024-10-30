# common-py

My common Python hacks

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation
To install the required dependencies, use:
```bash
pip install -r requirements.txt
```

## Usage

### Example 1: Handling Exceptions
```python
from commonpy.simpleexceptioncontext import SimpleExceptionContext

with SimpleExceptionContext(err_description="Example error handling"):
    # Your code here
```

### Example 2: Date and Time Utilities
```python
from commonpy import localize_it, unlocalize_it
import datetime

dt = datetime.datetime.now()
localized_dt = localize_it(dt)
unlocalized_dt = unlocalize_it(localized_dt)
```

## Features
- **SimpleExceptionContext**: Context manager for handling exceptions with customizable logging and traceback formatting.
- **Date and Time Utilities**: Functions to localize and unlocalize datetime objects.
- **Functional Helpers**: Various lambda functions for filtering dictionaries and mapping lists.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

## License
This project is licensed under the MIT License.
```

