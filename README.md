# wasm-extensions-learning

## 开发指南

### C++ 扩展

参考资料：[Write a Wasm Extension with C++](https://github.com/istio-ecosystem/wasm-extensions)

#### 环境准备

1. 安装 `bazel`

推荐使用 `Bazelisk` 作为 `bazel`。

可直接去 `github` 上下载对应的[二进制包](https://github.com/bazelbuild/bazel/releases)，并配置好环境变量即可直接使用。

2. 安装最小依赖

为了使用 `Bazel` 构建 `C++ WebAssembly` 扩展，需要安装依赖项 `python3` 等几个依赖。

#### 开发、测试、部署 `C++ WebAssembly` 扩展
