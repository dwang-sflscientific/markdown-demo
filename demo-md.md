# Jupyter notebook Commit Demo

1. Initialize notebook with both `ipynb` and `.md` formats.
2. Commit the initialized notebook.
3. Add new contents into notebook.
4. Commit the updated notebook.
5. Check commit difference in `.md` format and commit difference in `.ipynb` format.

### 1. initialize notebook

```{.python .input  n=1}
import pandas as pd
```

```{.python .input  n=2}
print("initalize notebook")
```

```{.json .output n=2}
[
 {
  "name": "stdout",
  "output_type": "stream",
  "text": "initalize notebook\n"
 }
]
```

### 2. update notebook

```{.python .input  n=5}
import numpy as np
```

```{.python .input  n=6}
print("update notebook")
```

```{.json .output n=6}
[
 {
  "name": "stdout",
  "output_type": "stream",
  "text": "update notebook\n"
 }
]
```
