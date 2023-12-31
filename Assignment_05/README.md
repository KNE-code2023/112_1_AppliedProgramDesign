# 應用程式設計 - 課後實作 05

## 問題描述 - 1
寫出一程式，輸入正整數 a、b (a <= b)，輸出 a、 b 之間 4 或 9 之倍數 (包含 a、b)，並算出「倍數數量」與「倍數總和」。

### 範例輸入
```
1
10
```
### 範例輸出
```
[4, 8, 9]，共有 3 個，總和為 21
```
### 如何使用
```bash
python Assignment_05_1.py
```
## 問題描述 - 2
撲克牌洗牌與發牌撲克牌有黑桃 ♠、 紅心 ♥、方塊 ♦、梅花 ♣ 四種花色，每一花色有 13 張牌。  
大老二紙牌遊戲是由四個玩家組成牌局。  
請撰寫一程式，可以隨機洗牌並發牌给四個玩家，最後將發牌結果列印在螢幕上與檔案中 (output.txt)。
### 範例輸入
```
無
```
### 範例輸出
```
玩家1: ['Q♣', 'K♥', '5♥', 'Q♠', '9♣', '3♦', '6♥', '8♥', '2♣', 'Q♦', 'J♣', 'A♥', '7♦']
玩家2: ['7♥', 'J♥', '2♠', '10♠', 'A♦', '10♣', '8♣', '9♦', '4♦', '2♦', '10♥', '10♦', 'A♠']
...
```
### 如何使用
```bash
python Assignment_05_2.py
```
## 問題描述 - 3
請統計附檔 (snow-white.txt) 內的英文字母 a 到 z 出現的次數 (不計大小寫)，並將統計結果列印文字輸出以及繪製為長條圖。  
橫軸是英文字母 a - z，縱軸是出現的次數。
### 範例輸入
```
無
```
### 範例輸出
```
{'a': 100, 'b': 121, 'c': 12, ......, 'z': 2}
```
### 如何使用
```bash
python Assignment_05_3.py
```

## 目錄結構
```bash
Assignment_05/
│
├─ data/
│  └─ snow-white.txt
│
├─ docs/
│  └─ output.txt
│
├─ src/
│  ├─ Assignment_05_1.py
│  ├─ Assignment_05_2.py
│  └─ Assignment_05_3.py
│
└─ README.md
```