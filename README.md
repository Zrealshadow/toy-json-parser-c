# Toy Json parser in pure C

follow the tutorial [link](https://github.com/miloyip/json-tutorial). 

The provided APIs can be checked in `leptjson.h`

> Just a toy project to get familier with C language in memory management and basic project technique.
>
> Chill project under the research pressure.



[]()### Build

```shell
mkdir build
cd build
cmake ..
./leptjson_test
```



user valgrind to check the leaked memory

```shell
valgrind --leak-check=full ./leptjson_test -s
```



### Future

it will be fun to re-write it in C++ using smart point or in Rust.





