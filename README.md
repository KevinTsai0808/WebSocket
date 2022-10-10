# WebSocket
> WebSocket是一種基於TCP連線的位於Application Layer的協定。在連線的初期和HTTP一樣，是透過client端請求，server才做回應，然而在連線建立後，雙方都能隨時將訊息傳遞給對方，因此使用WebSocket的效率較HTTP高
1. Server端建立Socket
2. Client端與Server端連接（透過TCP三向交握）
3. 連接後開始雙向傳輸資料（透過剛剛建立的TCP通道）
4. 關閉Client端的連線
