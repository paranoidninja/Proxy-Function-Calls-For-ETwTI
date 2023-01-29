# -Proxy-Function-Calls-For-ETwTI
The code is a pingback to the Dark Vortex blog: https://0xdarkvortex.dev/hiding-memory-allocations-from-mdatp-etwti-stack-tracing/

```
nasm -f win64 proxyHelper.asm -o proxyHelper.o
x86_64-w64-mingw32-gcc proxyAPICall.c proxyHelper.o -o proxyAPICall.exe
```
