# 说明

本分支主要为一些在非openwrt系统上使用openwrt相关库提供一些说明,主要用于开发环境(如ubuntu)。

# 编译

## 库依赖

- libjson-c:操作json
- lua:用于lua语言的相关模块。

## 步骤

- 创建目录(`mkdir build`)并进入目录(`cd build`)。
- 采用CMake创建工程文件(`cmake ../`)。
- 构建(`cmake --build .`)
- 安装到系统(`sudo cmake --build . -t install`)

