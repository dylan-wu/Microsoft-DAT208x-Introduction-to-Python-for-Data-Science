# 2D Numpy Arrays

<details><summary>Create a numpy array from this data: baseball = [[180, 78.4], [215, 102.7], [210, 98.5], [188, 75.2]] and print out the shape of the array</summary>
<p>

```python
# Create baseball, a list of lists
baseball = [[180, 78.4],
            [215, 102.7],
            [210, 98.5],
            [188, 75.2]]

# Import numpy
import numpy as np

# Create a 2D Numpy array from baseball: np_baseball
np_baseball = np.array(baseball)

# Print out the shape of np_baseball
print(np_baseball.shape)
```
</p>
</details>

```python
# Create baseball, a list of lists
baseball = [[180, 78.4],
            [215, 102.7],
            [210, 98.5],
            [188, 75.2]]

# Import numpy
import numpy as np

# Create a 2D Numpy array from baseball: np_baseball
np_baseball = np.array(baseball)
```

<details><summary>Print out the 50th row of the given baseball array above</summary>
<p>

```python
print(np_baseball[49,:])
```
</p>
</details>
