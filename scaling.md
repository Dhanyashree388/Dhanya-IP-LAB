```python
import numpy as np
import cv2 as cv

```


```python
img = cv.imread('orange.png')
res = cv.resize(img,None,fx=2, fy=2, interpolation = cv.INTER_CUBIC)
```


```python
cv.imshow('img',res)
cv.imshow("original pic",img)
cv.imshow("resize pic",res)
cv.waitKey(0)
cv.destroyAllWindows()
```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
