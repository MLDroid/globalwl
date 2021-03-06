# Global Weisfeiler-Lehman Kernels ###
Source code for our paper "Global Weisfeiler-Lehman Graph Kernels".

## Compile
Using `cmake` you can simply type `cmake cmake-build-debug`, otherwise (using `gcc`)

```Bash
$ g++ main.cpp src/.* -std=c++11 -o wlglobal -O2
```
In order to compile, you need a recent version of [Eigen 3](http://eigen.tuxfamily.org/index.php?title=Main_Page) installed on your system.

## Usage
You can select the kernel and parameters in `main.cpp`.

## More Data Sets
See [Benchmark Data Sets for Graph Kernels](http://graphkernels.cs.tu-dortmund.de) for more data sets.

## Contact Information
If you have any questions, send an email to Christopher Morris (christopher.morris at udo.edu).
