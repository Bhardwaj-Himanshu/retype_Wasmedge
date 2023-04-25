# Develop WasmEdge Plug-in

While the WasmEdge language SDKs allow registering host functions from a host (wrapping) application, developers should implement the host functions before compilation. For the other solutions, WasmEdge provides the plug-in architecture to load the plug-in shared library for easier extending of the host functions. With developing the plug-ins, WasmEdge SDKs in the supported languages can load and register the host functions from the plug-in shared libraries.

In current, developers can follow the guides to implement the plug-ins in [C API (recommended)](./1.md) or [C++](./2.md).

+++ Linux/Unix
```yml plugin.so
Plugins are easy, let's try them!
```
+++ Windows
```yml plugin.dll
At windows we love errors.
```
+++