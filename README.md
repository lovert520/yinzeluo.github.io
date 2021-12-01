## 和她一直牵手走下去


> <p></p>
 

<script>
 
  var oSpan = document.getElementsByTagName('span')[0];
 
  function tow(n) {
 
    return n >= 0 && n < 10 ? '0' + n : '' + n;
 
  }
 
  function getDate() {
 
    var oDate = new Date();//获取日期对象
 
    var oldTime = oDate.getTime();//现在距离1970年的毫秒数
 
    var newDate = new Date('2021/11/26 00:00:00');
 
    var newTime = newDate.getTime();//2019年距离1970年的毫秒数
 
    var second = Math.floor(( oldTime - newTime) / 1000);//未来时间距离现在的秒数
 
    var day = Math.floor(second / 86400);//整数部分代表的是天；一天有24*60*60=86400秒 ；
 
    second = second % 86400;//余数代表剩下的秒数；
 
    var hour = Math.floor(second / 3600);//整数部分代表小时；
 
    second %= 3600; //余数代表 剩下的秒数；
 
    var minute = Math.floor(second / 60);
 
    second %= 60;
 
    var str = '相识已有：' +  tow(day) + '<span class="time">天</span>'
 
        + tow(hour) + '<span class="time">小时</span>'
 
        + tow(minute) + '<span class="time">分钟</span>'
 
        + tow(second) + '<span class="time">秒</span>';
 
    oSpan.innerHTML = str;
 
  }
 
  getDate();
 
  setInterval(getDate, 1000);
 
</script>

  
### 认识时间

2021-11-26 10:36 pm

### 第一次见面

2021-11-29 6:15 pm

### 接触中犯下的错

#### 第一次见面中的过错

1. 见她时感觉过于漂亮，产生自惭形秽之心，表现不够自然。

2. 初次见面就过于肆无忌惮，导致印象很差。


