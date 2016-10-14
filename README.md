# gaussian_mixture_models
A C++ implementation of Gaussian Mixture Models (GMMs), with K-means initialization, Expectation Maximization and PCA

__Required packages:__
* Eigen3
* OpenMP

How to compile, after downloading the repository in **<PROJECT_ROOT>**:

```
cd **<PROJECT_ROOT>**
mkdir build
cd build
cmake ..
make -j9
```

A library _libgmm.so_ will be created in **<PROJECT_ROOT>**_/lib_
Several tests will be created in **<PROJECT_ROOT>**_/bin_

To use the library, simply execute in the **<PROJECT_ROOT>**_/build/_ directory:

```
make install
```

and use the Findgmms.cmake file that is available in the **<PROJECT_ROOT>**_/cmake_ directory.
