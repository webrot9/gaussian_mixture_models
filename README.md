# gaussian_mixture_models
A C++ implementation of Gaussian Mixture Models (GMMs), with K-means initialization, Expectation Maximization and PCA

__Required packages:__
* Eigen3
* OpenMP

How to compile, after downloading the repository in __<PROJECT_ROOT>__:

```
cd <PROJECT_ROOT>
mkdir build
cd build
cmake ..
make -j9
```

A library _libgmm.so_ will be created in __<PROJECT_ROOT>___/lib_
Several tests will be created in __<PROJECT_ROOT>___/bin_

To use the library, simply execute in the __<PROJECT_ROOT>___/build/_ directory:

```
make install
```

and use the Findgmms.cmake file that is available in the __<PROJECT_ROOT>___/cmake_ directory.
