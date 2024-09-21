# for more details refer https://docs.zephyrproject.org/latest/develop/env_vars.html#envvar-ZEPHYR_TOOLCHAIN_VARIANT

# set zephyr tool chain variant
export ZEPHYR_TOOLCHAIN_VARIANT=llvm
export LLVM_COMPILER=clang

# Building blinky for posix core kernel
west build -p always -b native_posix samples/basic/blinky