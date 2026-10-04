# ML Assignment 1: NumPy Vectorised Computation

## Repository Contents
- `assignment1_numpy.ipynb`: Jupyter notebook containing complete vectorized solutions for questions 1 to 11 with outputs visible.
- `clean.npy`: Serialized clean NumPy array from Question 11.
- `README.md`: Overview documentation and performance benchmark results.

## Question 8 Speed-Up Result
- **Data size**: 1,000,000 integer elements
- **NumPy `np.bincount` Execution Time**: ~0.95 ms
- **Standard Python Loop Execution Time**: ~95.0 ms
- **Measured Speed-Up**: **~100x speed-up** using NumPy vectorization over plain Python iteration.
