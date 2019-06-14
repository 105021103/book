---
description: (Foreach loop)
---

# 指定集合迴圈

 許多程式語言支援一種特別的迴圈，可以針對一個陣列中的元素或是一個集合中的所有成員進行迴圈中的指令，包括[Ada](https://zh.wikipedia.org/wiki/Ada)、[D語言](https://zh.wikipedia.org/wiki/D%E8%AA%9E%E8%A8%80)、[Smalltalk](https://zh.wikipedia.org/wiki/Smalltalk)、[Perl](https://zh.wikipedia.org/wiki/Perl)、[Java](https://zh.wikipedia.org/wiki/Java)、[C\#](https://zh.wikipedia.org/wiki/C%E2%99%AF)、[Visual Basic](https://zh.wikipedia.org/wiki/Visual_Basic)、[Ruby](https://zh.wikipedia.org/wiki/Ruby)、[Python](https://zh.wikipedia.org/wiki/Python)、[JavaScript](https://zh.wikipedia.org/wiki/JavaScript)、[Fortran 95](https://zh.wikipedia.org/wiki/Fortran#Fortran_95)等程式語言都有這類的迴圈結構：

```text
someCollection do: [:eachElement |xxx].

 foreach (item; myCollection) { xxx }

  foreach someArray { xxx }

   Collection<String> coll; for (String s : coll) {}

    foreach (string s in myStringCollection) { xxx }

    $someCollection | ForEach-Object { $_ }
   
      forall ( index = first:last:step... )
```

