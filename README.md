# H5.Note

子页面与传值
==============
    <script type="text/javascript" charset="utf-8">
      	mui.init({
		    subpages:[{
		      url:"main.html",//子页面HTML地址，支持本地地址和网络地址
		
		      styles:{
		        top:"100px",//子页面顶部位置
		        bottom:"0px",//子页面底部位置
		        width:"100%",//子页面宽度，默认为100%
		        height:"100%",//子页面高度，默认为100%
		      },
		      extras:{charlin_info:"this is content"}//额外扩展参数
		    }]
		  });
      	mui.ready(function(){
      	});
    </script>
