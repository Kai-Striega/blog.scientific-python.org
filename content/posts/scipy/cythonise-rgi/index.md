---
title: "Cythonise RGI"
date: 2024-03-11T10:04:47+11:00
draft: true 
description: "
SciPy claims to be highly performant. This performance is achieved with the help of languages like C, C++ and Fortran. In this blog post I will share how SciPy used [Cython](https://cython.readthedocs.io/en/latest/), a Python to C/C++ compiler, to more than double the performance of SciPy's [RegularGridInterpolator](https://docs.scipy.org/doc/scipy/reference/generated/scipy.interpolate.RegularGridInterpolator.html] class. 
"
tags: ["tutorials", [scipy]]
displayInList: true
author: ["Kai Striega"]

resources:
- name: featuredImage
  src: "my-image.png"
  params:
    description: "my image description"
    showOnTop: true
---

Some cool description before jumping in maybe?

## New cool Post

[Link](https://blog.scientific-python.org).

Here is some code

```python
import numpy as np

...
```

And maybe you need inline maths like $A=\pi r^2$, or more prominent equations:

$$ \sum_0^1 x $$

### Images

Images must be in PNG and compressed using a tool like `pngcrush` or
`pngquant`. For instance:

```bash
pngquant --ext .png --force my_figure.png
```

Another important aspect is alt-text. All figures must include alt-text.
This is very important for inclusiveness.

![my image description](my-image.png)
