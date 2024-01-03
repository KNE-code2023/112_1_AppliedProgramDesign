# 112 學年度第 1 學期 - 應用程式設計 課後實作集



## 課後實作 01
試找出 0 到 100 的整數中，符合 𝑎^3 + 𝑏^3 + 𝑐^3 = 𝑑^3 且 a < b < c < d 之 a, b, c, d 所有組合及數量。 

## 課後實作 02
寫出一程式，可輸入個數不受限的正整數或正浮點數。輸入負數則結束輸入。之後算出輸入數列之平均值、中位數、變異數、標準差 (四捨五入取至小數點後 2 位)。

## 課後實作 03
電價表如下，寫出一程式，輸入本月月份 x、目前使用度數 y，本月預算 z，可以輸出目前電費 w 元以及還可以使用的度數。
| 每月用電度數分段   | 夏月(6 ~ 9月)  | 非夏月      |
|  :----:            | :----:         | :----:      |
| 120 度以下部分     | 1.63元 / 度    | 1.63元 / 度 |
| 121 ~ 330 度部分   | 2.38元 / 度    | 2.10元 / 度 |
| 331 ~ 500 度部分   | 3.52元 / 度    | 2.89元 / 度 |
| 501 ~ 700 度部分   | 4.80元 / 度    | 3.94元 / 度 |
| 701 ~ 1000 度部分  | 5.66元 / 度    | 4.60元 / 度 |
| 1001 度以上部分    | 6.41元 / 度    | 5.03元 / 度 |

## 課後實作 04
寫出一程式，輸入 k，求費氏數列的 0 到 k 的數列。  
費氏數列具有下列性質：F(0) = 0, F(1) = 1, F( k+1 ) = F(k) + F( k-1 )。

## 課後實作 05
1. 寫出一程式，輸入正整數 a、b (a <= b)，輸出 a、 b 之間 4 或 9 之倍數 (包含 a、b)，並算出「倍數數量」與「倍數總和」。
2. 撲克牌洗牌與發牌撲克牌有黑桃 ♠、 紅心 ♥、方塊 ♦、梅花 ♣ 四種花色，每一花色有 13 張牌。  
大老二紙牌遊戲是由四個玩家組成牌局。  
請撰寫一程式，可以隨機洗牌並發牌给四個玩家，最後將發牌結果列印在螢幕上與檔案中。
3. 請統計附檔內英文字母 a 到 z 出現的次數 (不計大小寫)，並將統計結果列印文字輸出以及繪製為長條圖。  
橫軸是英文字母 a - z，縱軸是出現的次數。

## 課後實作 06
高鐵車廂售票問題。單一節高鐵車廂中，每節車廂有19排，每排座位有五個座位 (A、B、C、D、E)。因受疫情影響，售票需以梅花座的方式編排座位，且考慮車廂配重所以會以第 1 排 -> 第 19 排 -> 第 2 排 -> 第 18 排 -> 第 3 排 -> 第 17 排等次序販售。  
請撰寫一程式，可輸入購票數量 (最多限購 4 張票)，以梅花座為原則，輸出座位編號。  

※ 座位的編排限定在單一車廂內，售票數量不可超出單一車廂可容納的數量。

## 課後實作 07
用直方圖來統計單一圖片中不同像素值的數量，並以像素值為横軸、像素數量為縱軸來繪製圖表。圖片的直方圖統計如集中在特定範圍將使圖片看起過暗或是過亮。  
請設計一程式可以自動調整過亮或過暗的圖片，使圖片中的物件可以明顯呈現。此程式需可以讀入指定檔案、轉成灰階圖、調整像素值、將調整後的圖片另存新檔，同時顯示調整前後的直方圖於螢幕上。

## 課後實作 08
請讀入 csv 資料表並完成下列統計圖。
1. 顯示正常流量與 DDoS 流量占比與數量的圓餅圖。
2. 顯示統計 Destination Port 分布的直方圖。
3. 顯示統計 Fwd Packet Length Std 分布的直方圖。
4. 顯示橫軸是 Destination Port，縱軸是正常流量的 Average Packet Size 和其標準差，以及 DDoS 流量的 Average Packet Size 和其標準差。
5. 顯示橫軸是 Destination Port，縱軸是正常流量的 Fwd Packets/s 和其標準差，以及 DDoS 流量的 Fwd Packets/s 和其標準差。

※ 4 和 5 的顏色設定依序為: 紅色、綠色、黃色、藍色。

## 課後實作 09
使用附件程式完成下列測試。  

觀察不同回合數設定對於損失值與準確度的影響，並將實驗結果填入下表，其餘參數保持預設值。  

|epochs| loss |accuracy|
|:----:|:----:|:----:  |
|  5   |||
| 10   |||
|  20  |||
|  40  |||

找出訓練樣本的批次數量對於訓練模型的損失值、準確度與訓練時間的影響，並將實驗結果填入下表，其餘參數保持預設值。  

|batch_size|loss  |accuracy|耗時 (秒)|
|    :----:|:----:|:----:  |    ----:|
|50        ||  |     |
|100       ||  |     |
|200       ||  |     |
|400       ||  |     |

找出最佳激活函數，在卷積網路的架構中，有兩組激活函數需要設定，分別在輸入層和隱藏層，以及輸出層。  
請比較當輸出層激活函數固定為 softmax 時，輸入層和隱藏層激活函數分別為 relu、sigmoid、tanh 時的效能差異，並將實驗結果填入下表，其餘參數保持預設值。  

|Activation Function|loss  | accuracy  |耗時 (秒)|
|:----              |:----:|:----:     |----:    |
|relu               ||     |       |
|sigmoid            ||     |       |
|tanh               ||     |       |

找出最佳的參數組合以及效能改善結果填入下表。
|參數名稱                            |原始設定值|修改後的值|備註| 
|:----                               |:----:    |  :----:  |:--:|
|epochs                              |10||| 
|batch size                          |2000||| 
|activation function (input/hidden layer)|relu||| 
|activation function (output layer)      |softmax||| 
|Loss                                |||| 
|Acc                                |||| 

## 課後實作 10
任選之前的作業程式五項，註記為 A, B, C, D, E。  
設計一組程式，可以顯示文字型的選單，選單上有 A-E 與 Z 六個選項，如輸入選項 A，程式會啟動 A 程式，執行完畢後會回到選單．如輸入選項 Z，則退出選單。