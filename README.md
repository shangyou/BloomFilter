# BloomFilter
基于共享内存的 `BloomFilter` 库。

## Require

`SWOOLE`
`PHP-X`
`PHP >= 7.0`

## 安装使用

```bash
mkdir build
cd build
cmake ..
make && make install
```
or 

```bash
make && make install
```

到`php.ini`添加`extension=BloomFilter.so`