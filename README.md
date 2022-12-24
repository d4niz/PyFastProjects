# WinterClicker
This is a simple Auto-Clicker

Max clicks per second `1101`

# Instalation
First if you dont have Python3 you need to install it going [here](https://www.python.org/downloads/) and download the Python 3.11.1 version

Type this to download the library
```cmd
pip install *lib*
```

# Code

```py
import time
import keyboard
import mouse
```

```py
while True:
    if keyboard.is_pressed("1"):
        mouse.click()
    time.sleep(0.0000001)
```


# Usage

Type in cmd and use it.

For stop type in cmd `Ctrl + c`

```py
python3 {cd of the main.py}
```
