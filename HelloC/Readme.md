# cmake build

```sh
mkdir build && cd build
cmake .. -G "MSYS Makefiles"
make
./helloc.exe
```

# vscode cmake setting

```json
{
  "cmake.configureOnOpen": true,
  "cmake.cmakePath": "C:\\msys64\\mingw64\\bin\\cmake"
}
```