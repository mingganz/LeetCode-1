### 2375.Construct-Smallest-Number-From-DI-String

首先我们知道，必须将尽量小的字符放在前面使用。

我们将pattern前加上一个“I”，这样pattern的长度就与字符串相等。我们发现，将每个“IDD...D”视作一个section，那么后一个section必然要完全高于前一个section。我们虚拟地令当前的最大字符是0，然后把整个字符串的相对走势都表达出来后，其余位置的字符相应抬高即可。