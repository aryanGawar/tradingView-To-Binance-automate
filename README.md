# tradingView-signal-to-binance-future
 This is Server Site Script Which takes webhook from trading view and order on Binance


Before run this :
  Changes :
      1. Add "Token" field in "userData.json" : which matches with your webhook
      2. Add API and SECRET API of your binance account to "userData.json"
      3. Change "userName" and "pass" in "userData.json"
 
 
 Example of Webhook Syntex:
     In plain test:
     
     TOKEN=abcd
     SYMBOL=BTCUSDT
     SIGNAL=LONG
     QTY=0.01
     EXCHANGE=BINANCE
  
  SIGNAL Fields: 
     
     LONG        (Buy)
     SHORT       (Sell)
     CLOSE_LONG  (Close Buy Position)
     CLOSE_SHORT (Close Sell Position)
     
