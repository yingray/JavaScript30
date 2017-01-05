# Day1: 用鍵盤打鼓

本挑戰的筆記重點如下：

### keydown、transitionend監聽事件的運用

keydown事件是按下去當下就會激活，我們可以從傳進來的參數event，找出他有keyCode的屬性，
來取得你所按下的鍵盤是哪一個按鈕，
另外可以去 [http://keycode.info/](http://keycode.info/) 來查找我們欲求的按鍵編號。

transitionend用來監聽節點在style變化完成後的事件，有變化幾個style屬性就會發幾個event給你，所以選擇一個關鍵的變化屬性，
如本次練習為transform。

### audio 想要馬上重置時間

`audio.currentTime = 0;` 來重置時間

### 純js的addClass

取得DOM節點後，呼叫classList，在呼叫add方法來addClass。
remove則為removeClass。

### 快速實體化一個新的Array

`const array = Array.from();`迅速建立一個矩陣，詳細：
[MDN: Array.from()](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Global_Objects/Array/from)