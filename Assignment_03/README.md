# 應用程式設計 - 課後實作 03

## 問題描述
電價表如下，寫出一程式，輸入本月月份 x、目前使用度數 y，本月預算 z，可以輸出目前電費 w 元以及還可以使用的度數。
| 每月用電度數分段   | 夏月(6 ~ 9月)  | 非夏月      |
|  :----:            | :----:         | :----:      |
| 120 度以下部分     | 1.63元 / 度    | 1.63元 / 度 |
| 121 ~ 330 度部分   | 2.38元 / 度    | 2.10元 / 度 |
| 331 ~ 500 度部分   | 3.52元 / 度    | 2.89元 / 度 |
| 501 ~ 700 度部分   | 4.80元 / 度    | 3.94元 / 度 |
| 701 ~ 1000 度部分  | 5.66元 / 度    | 4.60元 / 度 |
| 1001 度以上部分    | 6.41元 / 度    | 5.03元 / 度 |
### 範例輸入
```
6  
200  
500
```
### 範例輸出  
```
電費 386 元，尚可用 47.9 度
```
