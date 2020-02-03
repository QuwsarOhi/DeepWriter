# DeepWriter
Implementation of ["DeepWriter: A Multi-Stream Deep CNN for Text-independent Writer Identification"](https://arxiv.org/abs/1606.06472)

Contains the DeepWriter and HalfDeepWriter network architecture implementation.
A random image stripping is also implemented.

Modify the loadData() function to work with dataset.
The X must contain image of shape (row, column, 1) and y must contain target class.
