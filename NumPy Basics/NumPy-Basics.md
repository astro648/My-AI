# NumPy Basics
### You can view the outputs much better on the `Numpy-Basics.ipynb` Jupyter notebook in the same subdirectory as this `.md` file! Github has built-in support for Jupyter notebooks and compilation results.
 - To import NumPy, run `import numpy as np` With this, you don't need to reference numpy as numpy, it is shortened to np.
 - Make a list: `myList = [1,2,3]`  List is named `myList` and has values `1,2,3`
 - To check the type of something, do `type(myList)` This checks the type of the list `myList`. As we have stated in the previous step, `myList` is a list.
 - To convert `myList` into a NumPy array named `myArray`, run `myArray = np.array(myList)` . We can check this by simply running `myArray`, which should now show us `array([1,2,3])`. If we check the type of our array by running `type(myArray)`, it should show `numpy.ndarray` which means that the list has been converted to a numPy array.
 - `np.arange(0,10)` outputs `array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])`. It creates an array of values starting at 0 and goes for 10. That is why it stops at 9.
 - `np.arange(0,101,2)` outputs `array([  0,   2,   4,   6,   8,  10,  12,  14,  16,  18,  20,  22,  24,
        26,  28,  30,  32,  34,  36,  38,  40,  42,  44,  46,  48,  50,
        52,  54,  56,  58,  60,  62,  64,  66,  68,  70,  72,  74,  76,
        78,  80,  82,  84,  86,  88,  90,  92,  94,  96,  98, 100])` It creates an array of values starting at 0 and going to 101 but only shows the values that are even.
 - `np.zeros(5)` displays 5 zeros. Output: `array([0., 0., 0., 0., 0.])`
 - `np.zeros(5,5)` displays 5 rows and 5 columns of zeros. This is a 2-dimensional array. Output: `array([[0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0.]])`
 - `np.zeros((2,5))` displays 2 rows and 5 columns of zeros. Output: `array([[0., 0., 0., 0., 0.],
       [0., 0., 0., 0., 0.]])`
 - `np.ones((5,5))` works the same as `np.zeros(5,5)` but it shows ones instead of zeros. Output: `array([[1., 1., 1., 1., 1.],
       [1., 1., 1., 1., 1.],
       [1., 1., 1., 1., 1.],
       [1., 1., 1., 1., 1.],
       [1., 1., 1., 1., 1.]])`
 - Let's say we want to make a NumPy variable, called `Var1` with an array from 0-10.  Run `Var1 = np.arange(0,11)` 
