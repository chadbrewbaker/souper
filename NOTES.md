
```bash
#had to goose the c++20 settings on the alive2 build
CC=../llvm-Release-build/bin/clang cmake -DCMAKE_CXX_FLAGS=" -std=c++20" ../alive2

#had to set the library path in the souper build to get libzstd
LIBRARY_PATH=/opt/homebrew/lib   make
```
