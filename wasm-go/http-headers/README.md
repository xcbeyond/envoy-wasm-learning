# http_headers

This example handles http request/response headers events and log all headers.

本示例是基于[http_headers](https://github.com/tetratelabs/proxy-wasm-go-sdk/tree/main/examples/http_headers)示例，来学习如何基于 Go 语言 实现 Envoy WASM 的扩展，并应用于服务网格 Istio。

详细参看：[基于 WASM 扩展 Envoy](https://xcbeyond.cn/istio-handbook/extensibility/extending-envoy-proxy-with-webassembly.html)

编译 wasm：

```bash
tinygo build -o ./http-headers.wasm -gc=custom -tags='custommalloc nottinygc_envoy' -scheduler=none -target=wasi ./main.go
```
