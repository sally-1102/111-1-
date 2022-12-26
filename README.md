# 111-1人工智慧期末報告-股票預測
> 該內容僅作為111學年度第一學期,跨領域課程-人工智慧期末報告之用
> 

**使用LSTM神經網絡預測股票價格**
> LSTM(長短期記憶):一種時間循環網路系統,適用於預測/處理時間間隔或延遲非常長的事件
> 

**1.匯入模組及使用功能**
![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%B8%80%E6%AD%A5.jpg)

**2.上傳及讀取數據集**
> 如圖所示,在回應系統(黃線處)時若使用全形字母會造成無法辨識的情況(紅線處)
> 

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%BA%8C%E6%AD%A5.jpg)

**3.從DataFrame分析收盤價**
![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%B8%89%E6%AD%A5.jpg)

**4.按日期時間對數據及進行排序並過濾『日期』『關閉』列**
![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E5%9B%9B%E6%AD%A5.jpg)

**5.正規化新過濾的數據集**
> 這步驟在做執行階段時有發生錯誤（沒有截到圖片），但再一次執行過前面的步驟以後就可以順利執行，推測是因為與上課時用的裝置不同所導致。
> 

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%BA%94%E6%AD%A5.jpg)

**6.建構和訓練LSTM模型**
> 第六步和第五步一樣,剛開始時發生執行錯誤,重新跑過之後就恢復正常
> 

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E5%85%AD%E6%AD%A5.jpg)

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E5%85%AD%E6%AD%A5%E9%A9%9F%E9%8C%AF%E8%AA%A4.jpg)

**7.取一個數據集樣本,使用LSTM模型進行股票價格預測**

**8.保存LSTM模型**

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%B8%83%E5%85%AB%E6%AD%A5.jpg)

**9.將預測庫存成本與實際庫存成本可視化**

![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%B9%9D%E6%AD%A5%E4%BB%A3%E7%A2%BC.jpg)
![](https://github.com/sally-1102/sally-1102.github.io/blob/main/%E5%9C%96%E5%BA%AB/%E7%AC%AC%E4%B9%9D%E6%AD%A5%E7%B5%90%E6%9E%9C.jpg)

# 心得總結
  　　在做期末報告時最難的部分並不是將上課的內容用Google Colab呈現出來,而是將過程、筆記等等的內容變成部落格的方式呈現出來。因為在做上課內容時有講義可以對照結果和過程，但是在將其弄成部落格時遇到問題只能去google查找，而且也因為版本或是先備知識不足的關係常常看得雲裡霧裡，最後結果就是把筆記變成部落格的時間遠大於將上課內容實際操作一遍。
  
# 組員名單
11018101 黃思璇 

11018102 呂姿頤

11018106 梁詩敏

11018150 劉芳瑜
