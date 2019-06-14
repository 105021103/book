---
description: break
---

# 提早結束迴圈

 當使用指定次數的迴圈查表時，會希望在查到需要的資料時就可以直接結束迴圈的進行，有些程式語言可以用`break`或`exit`的指令達到這様的功能，這些指令會結束這個迴圈，接著會執行迴圈後面的指令。若此迴圈在副程式中，也可以用`return`中斷迴圈的進行， 同時離開副程式。

```text
 //在迴圈裡會印出0,1,2,3,4,5,
        for(int i = 0 ; i < 10;i++)
        {
            System.out.print(i+",");
            if(i==5)//當i==5時就先中斷這個迴圈了
                break;
        }
```


