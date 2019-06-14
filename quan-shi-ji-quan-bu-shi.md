# 迴圈變式及迴圈不變式

迴圈變式及迴圈不變式是判斷迴圈正確性的工具。

迴圈變式是一個初值不為負的整數表示式，在每次執行迴圈時迴圈變式的數值需減少，但在正常的迴圈執行過程中迴圈變式的數值不會變成負值。迴圈變式用來確保迴圈會結束。

迴圈不變式是一個和迴圈有關的判斷式，在第一次進入迴圈之前，迴圈不變式的值需為真，在後續每一次執行迴圈時，其值也要為真。當迴圈正確的結束時，其終止條件和迴圈不變式都會成立。迴圈不變式可用來監控在迴圈進行時，某一指定性質的狀態。

像是[Eiffel](https://zh.wikipedia.org/wiki/Eiffel)之類的程式語言本身就有支援迴圈變式及迴圈不變式，其他語言可能需要有附加元件才能支援此功能，例如[Java](https://zh.wikipedia.org/wiki/Java)就需要配合[Java建模語言](https://zh.wikipedia.org/w/index.php?title=Java%E5%BB%BA%E6%A8%A1%E8%AA%9E%E8%A8%80&action=edit&redlink=1)規範的[loop statements](http://www.eecs.ucf.edu/~leavens/JML//jmlrefman/jmlrefman_12.html#SEC168)才能支援此機能。

