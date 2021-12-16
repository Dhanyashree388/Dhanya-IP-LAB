```python
import numpy as np
import cv2 as cv
```


```python
img = cv.imread('orange.png',0)
rows,cols = img.shape
```


```python
M = cv.getRotationMatrix2D(((cols-1)/2.0,(rows-1)/2.0),90,1)
dst = cv.warpAffine(img,M,(cols,rows))
```


```python
cv.imshow('img',dst)
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
