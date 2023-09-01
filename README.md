# 33.
const int i = 10;
int& r = const_cast<int&>(i); // 常量转换，将const int转换为int
