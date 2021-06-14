## Welcome to My Page

You'll have to create another txt file where you will give the text to be spammed....

### Code


```
import pyautogui
import time

time.sleep(5)
f = open("text", 'r')
for word in f:
    pyautogui.typewrite(word)
    pyautogui.press("enter")
```
