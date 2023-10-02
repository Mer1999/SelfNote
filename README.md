# SelfNote
随想随写，没有条理
目标笔耕不辍

## 2023/10/3
了解了python中的dict.get(key[, value])命令，曾经在查找字典内value值时还要先if key in dic来防止dict[key]直接访问报错（感觉不如STL自动赋初值0。。。），十分冗杂。而这只需要dict.get(key, 0)就可以完美替代，第二个可选参数value代表key不在字典内时的返回值。
