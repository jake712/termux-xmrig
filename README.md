# termux-xmrig
Run xmrig on android termux


```
pkg update -y && pkg upgrade -y
```
```
pkg install clang make pkg-config libuv openssl git wget cmake -y
```
```
git clone https://github.com/xmrig/xmrig.git
```
```
cd xmrig
```
```
mkdir build && cd build
```
```
cmake .. -DWITH_HWLOC=OFF -DWITH_OPENCL=OFF -DWITH_CUDA=OFF
```

```
make -j$(nproc)
```

```
./xmrig -o rx.unmineable.com:3333 -k -u POL:0x4da2a435251da9f103cc3fb2452a80c365e0d1fd.p#t2xb-3vc4 -p x -a rx/0 --donate-level 1 --threads 6 --randomx-1gb-pages
```
