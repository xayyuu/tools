
# ubuntu 查看系统性能
- top 命令查看cpu利用率。
    > top命令查看时，可能会发现有cpu利用率超过100%的情况出现，这是因为多核的情况，此时按数字键盘1,可以分别看见每个核的使用情况。

- free 命令查看内存利用率。
    > 这里又有一个坑。就是free和used加起来不等于total，实际上还有buffer和cached的内存。不过作为普通用户，如果swap都还没用到，就无需担心内存不够用。
    > 资料：http://cizixs.com/2015/10/01/linux-memory-management-through-free
