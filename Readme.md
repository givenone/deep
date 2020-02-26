[tensorflow에서 gpu 사용하기] (https://www.tensorflow.org/install/gpu)

0. tensorflow-gpu 사용 (gpu를 사용할 수 있는 기기에서는 자동으로 tensorflow-gpu 버젼을 따른다)
1. nvidia cuda 설치 **external하게 nvidia drive를 사용해주기 위해서 cuda를 위한 drive가 필요하다.
- version을 잘 체크해야 한다. 나의 경우 10.2를 linux 환경에서 설치했다. (upgrade시 시간이 오래 걸림)
https://developer.nvidia.com/cuda-downloads?target_os=Linux&target_arch=x86_64&target_distro=Ubuntu&target_version=1804&target_type=deblocal

[참고] (http://blog.ju-ing.com/2018/04/05/CUDA-8.0-to-9.0/)
2. cudnn설치.
- cuda version에 맞는 cudnn을 설치해야한다.
https://developer.nvidia.com/rdp/cudnn-download
* 로그인 필요.
