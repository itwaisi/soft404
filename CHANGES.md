# changes by itwaisi

- change `import httplib` to `import http.client` and update all references
- change `import urllib2` to `import urllib.request` and update all references
- change `import urlparse` to `import urllib.parse` and update all references
- change `except Redirect, e:` to `except Redirect as e:`
- change `socket.timeout, ValueError), e` to `socket.timeout, ValueError) as e`
- update all `print` commands to have have parentheses