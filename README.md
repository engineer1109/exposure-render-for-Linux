# exposure-render-for-Linux  
Super Volume Render of Monte Carlo Path tracing for Linux  
## Introduction  
The code is a Linux distribution of exposure render.

## Dependency  
QT 5.14   (maybe 5.12+)  
CUDA 11.0  (maybe 10.0+)  
VTK 8.2  
GCC 9  

## BUILD && RUN  
```
cd source
mkdir build  
cd build
cmake ..  
make  
./ExposureRender  
```

## Reference  
* [An interactive photo-realistic volume rendering framework](http://graphics.tudelft.nl/Publications/kroes_exposure_2012)  
T. Kroes, F. H. Post, C. P. Botha
* [Visibility sweeps for joint-hierarchical importance sampling of direct lighting for stochastic volume rendering](http://graphics.tudelft.nl/Publications-new/2015/KEE1)  
T. Kroes, M. Eisemann, E. Eisemann
