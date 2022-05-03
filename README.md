# py-attire-logger
This is a client library written in Python 3 that can be used by other Python programs/scripts to parse and generate ATTiRe formatted log files.

## Files for local dev

For use with local venv installation with setup.py projects 

**Requirements.txt**
```ini
pydantic~=1.9.0
```

**setup.py**
```python
from setuptools import setup

packages = ['py_attire_logger']

package_data = {'': ['*']}

setup_kwargs = {
    'name': 'py-attire-logger',
    'version': '0.1.0',
    'description': '',
    'long_description': None,
    'author': 'Your Name',
    'author_email': 'you@example.com',
    'maintainer': None,
    'maintainer_email': None,
    'url': None,
    'packages': packages,
    'package_data': package_data,
    'python_requires': '>=3.6,<4.0',
}


setup(**setup_kwargs)
```
