

## 珍藏 情书


> <p id='daojishi'>这是倒计时</p>


### 第一次相知

2021-11-26 10:36 pm

> 三杯两盏淡酒，亦足以畅叙幽情。

### 第一次相见

2021-11-29 6:15 pm

> 与君相逢，便胜人间无数。

### 第一次约会

2021-12-04 4：23 pm

> 相思相见知何日，此时此夜难为情。

可以一起吃街边小吃，一起手牵手闲逛，这就是我曾经梦想中的恋爱，简单而又纯粹的在一起。

 
### 接触中犯下的错

1. 初见时过于惊艳，心中自惭形秽，表现不够自然。
 
2. 竟然迟到了，我能感受到她心里的那种失望感，这种错误再不允许了！ 

3. 关心是一种行动而不是言语表达。

4. 言者无心，听者有意，从口而出的话语需要适当三思。

5. 喜欢是感性的行为，当开始理性的量化喜欢程度时，就已经是在怀疑爱？

    当对两个女生进行选择时，那他们都输了。（这个例子具体什么意思？我是在做选择吗？下一步的工作规划和对她的选择？
    
    事业的规划和对感情的追求，两者不冲突的！

 
### 她告诉我的道理
 
1. 想清楚自己想要什么。
 
2. 信任和真诚，是维系感情的基础。
 
3. 相处时自然融洽最重要，过于迁就对方，会逐步积累不舒适的情绪，渐渐心生隔阂。

4. 喜欢一个人，心中会时刻很欢喜，表达情绪也是发自内心。
 
5. 爱是一种无私的自发的行为，不参杂交换和要求对等；相爱是相互的。

6. 主动自发的了解她的需求，来自内心的关心所作出的行为。

### 喜欢是感性发自内心的行为

1. 用一天会想起她几次来量化喜欢的程度是愚蠢的！感情是不可量化的，可能一天只会想念她一次，是因为晚风吹起时的冰冷让我担忧体寒柔弱的她；可能一天的每一秒都在思念她，是因为她已经住在我的心里随着心跳一次次的想起她。

2. 时间的成本考量，是必要的，但并不是两人在一起必须的。



 

<script>
 
$(document).ready(function(){
 $('title').text('殷仄洛❤余生');
 var h1 = document.getElementsByTagName('h1')[0];
 h1.innerHTML="执子之手 与子偕老";
 var dn1 = document.getElementById('forkme_banner');
 dn1.style.display='none';
 var dn2 = document.getElementsByTagName('footer')[0];
 dn2.style.display='none';
 
  var oSpan = document.getElementById('daojishi');
  function tow(n) {
 
    return n >= 0 && n < 10 ? '0' + n : '' + n;
 
  }
 
  function getDate() {
 
    var oDate = new Date();//获取日期对象
 
    var oldTime = oDate.getTime();//现在距离1970年的毫秒数
 
    var newDate = new Date('2021/11/26 22:36:00');
 
    var newTime = newDate.getTime();//2019年距离1970年的毫秒数
 
    var second = Math.floor(( oldTime - newTime) / 1000);//未来时间距离现在的秒数
 
    var day = Math.floor(second / 86400);//整数部分代表的是天；一天有24*60*60=86400秒 ；
 
    second = second % 86400;//余数代表剩下的秒数；
 
    var hour = Math.floor(second / 3600);//整数部分代表小时；
 
    second %= 3600; //余数代表 剩下的秒数；
 
    var minute = Math.floor(second / 60);
 
    second %= 60;
 
    var str = '相知相识三两天：' +  tow(day) + '<span class="time">天</span>'
 
        + tow(hour) + '<span class="time">时 </span>'
 
        + tow(minute) + '<span class="time">分</span>'
 
        + tow(second) + '<span class="time">秒</span>';
 
    oSpan.innerHTML = str;
 
  }
 
  getDate();
 
  setInterval(getDate, 1000);
 });
</script>



