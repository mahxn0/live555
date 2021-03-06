For documentation and instructions for building this software,
see <http://www.live555.com/liveMedia/>

## Live555 jetson编译共享库
- 1. 下载live555 源码

- 2. 编译安装
  ```
  ./genMakefiles  linux-with-shared-libraries 

   make -j4
 
   make install PREFIX=./libs (指定安装位置)
  ```
