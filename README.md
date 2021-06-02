## Setup

```
mkdir -p build && cd build
conan install ..
cmake ..
```

## Build && Run

```
make main
./bin/main
```

## Test

```
make test
ctest
./bin/test
```