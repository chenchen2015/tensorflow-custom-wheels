# tensorflow-custom-wheels
Custom build tensorflow wheels optimized for AWS EC2 Instances

## Builds
| TF  |      OS      | Python & Compiler |     ARCH     | CUDA & cuDNN |          Opt flags         |                                                                        Install Command                                                                        |                                                                            Wheel                                                                            |
|:---:|:------------:|:-----------------:|:------------:|:------------:|:--------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|
|1.8.0| Amazon Linux |  3.6.5 GCC 4.8.5  | CPU (x86_64) |      N/A     | AVX AVX2 SSE4.1 SSE4.2 FMD | `pip install https://github.com/chenchen2015/tensorflow-custom-wheels/raw/master/1.8.0/tensorflow-1.8.0-cp36-cp36m-SSE41-SSE42-FMD-AVX-AVX2-linux_x86_64.whl` | [Download](https://github.com/chenchen2015/tensorflow-custom-wheels/raw/master/1.8.0/tensorflow-1.8.0-cp36-cp36m-SSE41-SSE42-FMD-AVX-AVX2-linux_x86_64.whl) |
