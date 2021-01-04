# build

```sh
make
./Hello.exe
```


```
x86_64-w64-mingw32-g++ `wx-config --cxxflags` `wx-config --libs` -c Hello.cpp -o Hello.o
```