# distribo
Python package for statistical distributions

# Installation

`pip install distribo`

# How to use (Examples)

### Example 1
```
>>> from distribo import Gaussian
```
Create a gaussian function with mean = 2 and standard deviation = 5
```
>>> gaussian_one = Gaussian(2,5)
```

Create another gaussian function with mean = 3 and standard deviation = 4
```
>>> gaussian_two = Gaussian(3,4)
```

Add two gaussian functions (outputs the new gaussian function with calculated mean, standard deviation)
```
>>> gaussian_one + gaussian_two
mean 5, standard deviation 6.4031242374328485
```
