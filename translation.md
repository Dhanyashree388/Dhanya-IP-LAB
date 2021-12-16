```python
import numpy as np
import cv2 as cv

```


```python
img = cv.imread('mango.jpg',0)
rows,cols = img.shape

```


```python
M = np.float32([[1,0,100],[0,1,50]])

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


```python

```


```python

```


```python

```


```python

```
