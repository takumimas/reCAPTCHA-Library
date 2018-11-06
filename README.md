# reCAPTCHA-Library

This is a reCAPTCHA-Library for Python3.

Can check reCAPTCHA token.

# How to use

1.Download recaptcha.py

2.import your Python source

```Python
from recaptcha import recaptcha
```
3.Call function and add key and token.
```Python
answer = recaptcha("your secret key","token")
```
4.Library return True or False.

If it is not robot,return True.

If it is robot,return False.
