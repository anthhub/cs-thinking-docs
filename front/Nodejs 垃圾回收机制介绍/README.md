# Nodejs 垃圾回收机制介绍

> 过年在家读了一下 [深入浅出Node.js], 颇有收获, 分享一下其中内存管理章节.

![深入浅出Node.js](https://img9.doubanio.com/view/subject/l/public/s27134708.jpg)


## 内存管理机制

    - C: 纯手工管理内存
    - C++:  手工管理 + 确定性析构 (RAII)
    - GC 语言: 垃圾回收
    - Rust: 借鉴 RAII 的所有权机制




 