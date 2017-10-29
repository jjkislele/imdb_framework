# imdb_framework
## for Sketch-based image retrieval
# What's this?
This project is forked from [mathiaseitz's imdb_framework](https://github.com/mathiaseitz/imdb_framework) which I am interested in.

Whole code is based on the paper ["Sketch-Based Shape Retrieval" - SIGGRAPH 2012](http://cybertron.cg.tu-berlin.de/eitz/projects/sbsr/) and the previous paper ["Sketch-based image retrieval: benchmark and bag-of-features descriptors" -  IEEE T VIS COMPUT GR 2011](http://cybertron.cg.tu-berlin.de/eitz/projects/sbsr/).

# Algorithm
Sketch-Based Shape Retrieval

1. GALIF: Gabor local line-based feature
2. BoF: Bag of Features

Sketch-based image retrieval: benchmark and bag-of-features descriptors

1. sHoG
2. BoF: Bag of Features

# Requirement before compile

* Qt lib and Qt creator

*Note:* Whole code is written by Qt creator, instead of VS. 

If you find the file named ".pri", you will immediatly understand it. The dependencies and include files will be find in ".pri". But I cannot use Qt creator very well, I have changed the Qt version to the MSVS version. If you're familiar with MSVS, you can fork my next repository named "imdb_framework_msvs"

* boost lib

USE AT LEAST FOUR CPU CORES TO COMPUTE!!!(depend on your hardware)

* openCV 2.x

# Related work in github

* [zddhub's opensse](https://github.com/zddhub/opensse/)

* [ialhashim's sketch-search](https://github.com/ialhashim/sketch-search/)

