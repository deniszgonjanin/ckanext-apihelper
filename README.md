# ckanext-apihelper

This extension is meant to add a few pages that will add a friendly interface
to talk to the action API. Install the extension and visit `/apihelper/`.
Requires CKAN Version 2.1.1 or higher.

## Installation
Clone the repo, install it with `python setup.py develop` or `pip install -e .`,
and add the following to your ckan.ini:
```
ckan.plugins = ... apihelper
```

![](http://okfnlabs.org/ckanext-apihelper/api-helper.png)
