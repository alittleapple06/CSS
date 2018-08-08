# CSS
CSS学习代码
<!--字体大小、加粗、斜体、上下划线、删除线、颜色-->
<p style =" font-size:120%;font-weight:400;text-decoration:line-through">we are the world</p>
<p style = "font-size:120%;color:rgb(200,110,110);font-weight:normal;font-style:italic;text-decoration:underline;">we are the world</p>    
<p style = "font-size:120%;color:rgb(70,90,300);font-weight:normal;font-style:italic;text-decoration:overline">we are the world</p>  
<!--行距-->
<p style = "line-height:0.6em">you are the best kitty</p>
<!--文字间距-->
<p style = "letter-spacing:2.6em">you are the best kitty</p>
<!--文本位置-->
<p style = "text-align:center">Roses are red</p>
<p style = "text-align:justify">&emsp;&emsp;这样的特工需要实现一个条件：他的命运是唯一确定的，而且在这个唯一确定的命运中，他一直执着地执行各种任务，从来没有超出预期。一旦他试图改变自己的命运，他的过去和未来都不复存在，以致于时空局最初就不会招募这样一个有问题的特工。</p>
<p style = "text-align:right">这样的特工需要实现一个条件：他的命运是唯一确定的，而且在这个唯一确定的命运中，他一直执着地执行各种任务，从来没有超出预期。一旦他试图改变自己的命运，他的过去和未来都不复存在，以致于时空局最初就不会招募这样一个有问题的特工。</p>
<!--文本缩进-->
<p style = "text-indent:9px">Roses are red</p>
<p style = "text-indent:90px">Roses are red</p>
<!--文字阴影-->
<p style = "text-shadow:-5px -5px 1px #FFAEB9;font-size:200%;color:#FF6347">Roses are red</p>
<p style="font-size: 40px;text-shadow: 4px 5px 1px #666666">Tamel</p>
<!--改变链接颜色-->
<style>
    a:link{color:#CD919E
    }
    a:hover{color:#D1EEEE;
        text-decoration:underline;
    }
    a:active{color:#8B8B83;
    }
    a:visited{color:#0F0F0F;
    }
</style>
<a href = "https://www.cxy61.com/index-image/index.html">胖鸟影视</a>
<!--类选择器，-->
<style>
    .center{
    text-align:center;
    font-size:200%;
    color:pink;
    text-decoration:underline;
    text-shadow:5px 5px 1px #FF6347;
    font-weight:300;}
</style>
<p class = "center">hello</p>
<p class = "center">show me the money</p>
<!--伪类-->
<style>
    .be:hover{background-color:pink;
    }
    .be:active{background-color:darkcyan;
    }
</style>
<button class = "be" type = "button">搜索</button>
<!--选择器，文本向左对齐，字体大小8PX，颜色为cyan-->
<style>
    .text{text-align:left;
        font-size:8px;
        color:cyan}
</style>
<p class = "text">今晚的月色真美</p>
    
    
    
    
    
    
