[1] 輸入與輸出 (USER INPUTS AND OUTPUT)
====================
[1.1] input 
--------------------
+1. 輸入圓形半徑，並計算面積:

```
# !/usr/bin/env python
# coding=utf-8

# Input(輸入):Prompt the user to enter a radius 
# eval(): 為 python 內建函數，用來執行一個字串表達式，並返回表達式的值
# [eval()] ==> <http://www.runoob.com/python/python-func-eval.html>
radius = eval(input("Enter a number for radius: "))

# Processing(處理):Compute area
area = radius * radius * 3.1415962

# Output(輸出):Display results
print("The area for the circle of radius", radius, "is", area)  //逗點間不要留空白
```

[1.2] 同時指定(Simultaneous Assignment )
-----------------------
```
# !/usr/bin/env python
# coding=utf-8

# Prompt the user to enter three numbers
number1, number2, number3 = eval(input("Enter three numbers separated by commas: "))

# Compute average
average = (number1 + number2 + number3) / 3

# Display result
print("The average of", number1, number2, number3, "is", average)

```




