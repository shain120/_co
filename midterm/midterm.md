# 期中
## 111210540 黃冠勝

### 第一週習題:
自行學習

[Not](https://github.com/shain120/_co/blob/master/01/Not.hdl)

[And](https://github.com/shain120/_co/blob/master/01/And.hdl)

[Or](https://github.com/shain120/_co/blob/master/01/And.hdl)

[Xor](https://github.com/shain120/_co/blob/master/01/And.hdl)

[Mux](https://github.com/shain120/_co/blob/master/01/Mux.hdl)

[DMux](https://github.com/shain120/_co/blob/master/01/Mux.hdl)

[邏輯圖&筆記](https://github.com/shain120/_co/blob/master/picture/Notes_240924_222321.pdf)

### 第二週習題:
查看pdf講義,自行學習

[Not16](https://github.com/shain120/_co/blob/master/01/Not16.hdl)

[And16](https://github.com/shain120/_co/blob/master/01/And16.hdl)

[Or16](https://github.com/shain120/_co/blob/master/01/Or16.hdl)

[Mux16](https://github.com/shain120/_co/blob/master/01/Mux16.hdl)

[Or8Way](https://github.com/shain120/_co/blob/master/01/Or8Way.hdl)

[Mux4Way16](https://github.com/shain120/_co/blob/master/01/Mux4Way16.hdl)

[Mux8Way16](https://github.com/shain120/_co/blob/master/01/Mux8Way16.hdl)

[DMux4Way](https://github.com/shain120/_co/blob/master/01/DMux4Way.hdl)

[DMux8Way](https://github.com/shain120/_co/blob/master/01/DMux8Way.hdl)

[邏輯圖](https://github.com/shain120/_co/blob/master/picture/Notes_241130.pdf)

### 第三週習題：
在網路尋找加法器相關圖,先自行學習,不會的部分再去向chatgpt詢問

[HalfAdder](https://github.com/shain120/_co/blob/master/02/HalfAdder.hdl)

[FullAdder](https://github.com/shain120/_co/blob/master/02/FullAdder.hdl)

[Add16](https://github.com/shain120/_co/blob/master/02/Add16.hdl)

[Inc16](https://github.com/shain120/_co/blob/master/02/Inc16.hdl)

[邏輯圖](https://github.com/shain120/_co/blob/master/picture/HW3.pdf)

### 第四週習題：
透過老師上課了解ALU架構,透過chatgpt與參考[ALU](https://people.duke.edu/~nts9/logicgates/ALU.hdl)

[ALU](https://github.com/shain120/_co/blob/master/02/ALU.hdl)

[筆記](https://github.com/shain120/_co/blob/master/picture/HW4.png)

### 第五週習題:

參考Nand2tetris

[Bit](https://github.com/shain120/_co/blob/master/03/a/Bit.hdl)

[Register](https://github.com/Jonathan-es/_co/blob/master/03/a/Register.hdl)

[RAM8](https://github.com/shain120/_co/blob/master/03/a/RAM8.hdl)

[RAM64](https://github.com/shain120/_co/blob/master/03/a/RAM64.hdl)

[筆記](https://github.com/shain120/_co/blob/master/picture/位元.pdf)

### 第六週習題:
透過上週習題去延伸到RAM512...,
PC運用Register、Inc16去實現了一個16 bit計數器
reset為1,輸出被設置為0
否則,如果load為1,輸出被設置為輸入值in
否則,如果inc為1,輸出增加1
如果以上條件都不滿足,輸出保持不變

[RAM512](https://github.com/shain120/_co/blob/master/03/b/RAM512.hdl)

[RAM4K](https://github.com/shain120/_co/blob/master/03/b/RAM4K.hdl)

[RAM16K](https://github.com/shain120/_co/blob/master/03/b/RAM16K.hdl)

[PC](https://github.com/shain120/_co/blob/master/03/a/PC.hdl)

### 第七週習題:
用Hack組合語言編寫,並參考chat gpt進行改進,loop功能,提高了程序的可靠性和效率

[mult](https://github.com/shain120/_co/blob/master/04/mult/mult.asm)

### 第八週習題
Fill實現了的累加功能,全部使用chat gpt進行

[Fill](https://github.com/shain120/_co/blob/master/04/fill/Fill.asm)

### 第九週習題
指令執行、算術運算、條件跳轉和內存訪問,使用And16和Mux16去執行輸入的指令,參考[cpu](https://people.duke.edu/~nts9/logicgates/CPU.hdl)和chat gpt

[CPU](https://github.com/shain120/_co/blob/master/05/CPU.hdl)

### 第十週習題
處理了不同記憶體區域的讀寫操作,memSel選擇不同的記憶體區域,使用DMux4Way根據memSel將load分配給不同的記憶體區域
RAM system中集成 RAM、keyboard、screen

[Ｍemory](https://github.com/shain120/_co/blob/master/05/Memory.hdl)

Computer將CPU、記憶體和ROM組合。程序存儲在ROM中,CPU從ROM讀取指令並執行,CPU與記憶體（包括RAM和I/O設備）進行數據交換
[Computer](https://github.com/shain120/_co/blob/master/05/Computer.hdl)

參考chat gpt與Nand2tetris了解整個架構與運行方式
-------------------------------------------------------------------------------------
### 參考
[學期筆記](https://github.com/shain120/_co/blob/master/picture/學期筆記.pdf)
