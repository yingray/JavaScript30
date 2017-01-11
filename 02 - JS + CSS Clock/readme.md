# Day2: 時鐘

本挑戰的筆記重點如下：

### CSS transform, transition

transform 可以用 rotate(?deg) 直接轉角度
transform-origin 可以調整變形的參考原點

transition(過渡) 將屬性變換的過程，在設定的時間內做一個平滑的變換
transition-timing-function 可以設定這個過程變化的方式

### Date

用 new Date() 取得當前時間，並用 getSeconds 等取得欲求參數

### style

JS可以呼叫節點的style方法來改變樣式，如 secondsHand.style.transform
