# TWSECrawler
## use Python to Get TWSE Price Data

* TWSE的這個股價抓取網站需要帶入的有兩個參數
   + 股票代碼(含櫃買的股票代碼也可以查詢)  
   + 另一個我是把他設定成timeInterval

   > 參數1可以一次傳入多個股票代碼使用 "|"隔開即可

    [TWSE股價範例連結](https://mis.twse.com.tw/stock/api/getStockInfo.jsp?ex_ch=tse_2330.tw|tse_2002.tw&json=1&delay=0&_=12156484978)


* [股票代碼資訊](http://isin.twse.com.tw/isin/C_public.jsp?strMode=2)
    + 未上市上櫃公開發行 strMode=1
    + 上市 strMode=2
    + 上市上櫃債券 strMode=3
    + 上櫃 strMode=4
    + 興櫃 strMode=5
    + 期貨及選擇權 strMode=6
    + 開放式證券投資信託基金 strMode=7
    + 未公開發行之創櫃板證券 strMode=8
    + 買賣黃金現貨 strMode=9
    + 外幣計價可轉換定期存單 strMode=10