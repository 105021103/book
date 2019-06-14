---
description: (for loop)
---

# 指定執行次數的迴圈

大部份程式語言都提供迴圈的指令，可以依指定的次數重覆執行一段程式。若指定的次數N小於1，程式語言會忽略整個迴圈不去執行，若指定的次數N為1，則迴圈只會執行一次。在迴圈進行時，迴圈計數器也會隨著變化，大部份的程式語言可以允許迴圈計數器上數或是下數，每次的變化量可以是1或是其他不為0的數值。

 C語言中傳統的for-loop包含三個部分：初始化、條件、遞增，這三個部分都是可有可無的

 以Java為例：

```text
for (INITIALIZATION; CONDITION; AFTERTHOUGHT) 
{
    // 程式主體
}
```

如果你要使用多個變數，則變數的種類要一致。條件的部分則是檢查是否離開這個迴圈，也就是讓程式碼往下執行。如果條件判斷為假，則離開迴圈。遞增在每跑一次迴圈都會重複執行一次。

以Java為例：

```text
for (int i=0; i<100; i++)   // Prints the numbers 0 to 99 (and not 100), each separated by a space.
{
    System.out.print(i);
    System.out.print(' ');
}
System.out.println();
```





