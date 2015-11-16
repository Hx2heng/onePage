# onePage

  OnePage -"All content in one page"
  
  一款基于jQuery || Zepto 的页面小插件，用css3的新特性使已指定宽高的内容按比例缩放在其父级容器里。
 
  Created by HuangXinZheng
  
  Created in 2015.6
  
  qq:397323988
  
  使用方法：
  使用前确保你的页面引入了jQuery或者Zepto。如果是zepto要修改一下源文件，把全局传入的参数``jQuery``改为``Zepto``。
  $('#div').onePage(); 


以下是例子：

html：
>         <div id="container">
		  <div id="content">
		      <!-- your content here-->
		  </div>
    	</div>

css:

>         #conterner{width:100%;height:100%;}
        #content{width:640px;height:1008px;}

js:
>         $('#content').onePage();
