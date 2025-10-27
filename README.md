# ntpc
A simple NTP client for Linux

# How to compile ?
gcc ntpc.c -o ntpc 

# How to use ?
```bash
Usage: ntpc server1 server2 ... 
Example: ntpc 0.asia.pool.ntp.org 1.asia.pool.ntp.org 2.asia.pool.ntp.org

```

cmake \
	-DCMAKE_C_COMPILER=gcc \
	-DCMAKE_CXX_COMPILER=g++ \
	-DCMAKE_INSTALL_PREFIX="/app_build/release" \
	-DCMAKE_BUILD_TYPE=Release \
