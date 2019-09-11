# background-slider

You can switch the image in the specified directory as a Windows background slide.
The background changes in the order of the file names.

When stopped, the background before execution is restored.

## How to use

#### supported os

Windows10

#### setup

Please write path into 'path.txt'.

ex.

```
D:\bgimg
```

#### run

```
> python bg.py
```

#### stop

Ctrl + C

# used

* [ctypes](https://docs.python.org/ja/3/library/ctypes.html)
* [SystemParametersInfoW function](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-systemparametersinfow#parameters)
