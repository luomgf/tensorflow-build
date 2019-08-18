# tensorflow-build
tensorflow build binary . ,suport SSE4.1、SSE4.2、AVX、AVX2、FMA,ver:v1.14.0-rc1

[toc]

# mac,tf-v1.14.0-rc1
##  config
| tf | Java | Bazel | python | numpy| Mac |download|
| --- | --- | --- | --- | --- | --- | --- |
| Tf-v1.14.0-rc1 | jdk8 | 0.25.2 | 3.6.3 |1.16|macOs Mojave 10.14.6,intel i5,16G,intel 650|[download](https://media.githubusercontent.com/media/luomgf/tensorflow-build/master/tensorflow-1.14.0rc1-cp36-cp36m-macosx_10_6_intel.whl)|

## requirement.txt 
```
absl-py==0.7.1
astor==0.8.0
gast==0.2.2
google-pasta==0.1.7
grpcio==1.23.0
h5py==2.9.0
Keras==2.2.4
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0
Markdown==3.1.1
numpy==1.16.0
protobuf==3.9.1
PyYAML==5.1.2
scipy==1.3.1
six==1.12.0
tensorboard==1.13.1
tensorflow-estimator==1.14.0
termcolor==1.1.0
Werkzeug==0.15.5
wrapt==1.11.2
```

## build process
### time
```
INFO: Elapsed time: 15058.232s, Critical Path: 302.71s
INFO: 15504 processes: 15504 local.
INFO: Build completed successfully, 15898 total actions
```
### end flag
```
[18,663 / 18,670] 4 actions running
```

### project time
12h
