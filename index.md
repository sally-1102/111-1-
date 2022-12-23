# 111-1人工智慧期末報告-股票預測

> 該內容僅作為111學年度第一學期，跨領域課程－人工智慧期末報告之用。
> 
## 使用 LSTM 神經網絡預測股票價格

> LSTM(長短期記憶)：一種時間循環網路系統，適用於預測、處理時間間隔／延遲非常長的事件
>
1.  **匯入模組及使用功能**
![第一步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%B8%80%E6%AD%A5.jpg)

2.  **上傳及讀取數據集**
![第二步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%BA%8C%E6%AD%A5.jpg)

3.  **從DataFrame分析收盤價**
![第三步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%B8%89%E6%AD%A5.jpg)

4.  **按日期時間對數據集進行排序並過濾『日期』和『關閉』列**
![第四步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E5%9B%9B%E6%AD%A5.jpg)

5.  **正規化新過濾的數據集**
![第五步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%BA%94%E6%AD%A5.jpg)

6.  **構建和訓練 LSTM 模型**
![第六步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E5%85%AD%E6%AD%A5.jpg)

7.  **取一個數據集樣本，使用 LSTM 模型進行股票價格預測**
8.  **保存LSTM模型**
> ![第七八步](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%B8%83%E5%85%AB%E6%AD%A5.jpg)

9.  **將預測庫存成本與實際庫存成本可視化**
![第九步代碼](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%B9%9D%E6%AD%A5%E4%BB%A3%E7%A2%BC.jpg)
![第九步結果](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E7%AC%AC%E4%B9%9D%E6%AD%A5%E7%B5%90%E6%9E%9C.jpg)
