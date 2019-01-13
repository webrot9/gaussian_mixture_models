# gaussian_mixture_models
A C++ implementation of Gaussian Mixture Models (GMMs), with K-means initialization, Expectation Maximization and PCA

__Required packages:__
* Eigen3
* OpenMP

How to compile, after downloading the repository in *PROJECT_ROOT_DIR*:

```
cd PROJECT_ROOT_DIR
mkdir build
cd build
cmake ..
make -j9
```

A library _libgmm.so_ will be created in *PROJECT_ROOT_DIR*_/lib_

Several tests will be created in *PROJECT_ROOT_DIR*_/bin_

To use the library, simply execute in the *PROJECT_ROOT_DIR*_/build/_ directory:

```
make install
```

and use the Findgmms.cmake file that is available in the *PROJECT_ROOT_DIR*_/cmake_ directory.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
