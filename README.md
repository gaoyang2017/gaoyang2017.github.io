
<html>

<head>
  <title>Blog-GY2017</title>
  <meta name="description" content="Blog-GY2017" />
  <meta name="keywords" content="Blog-GY2017" />
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
  <!--<link rel="stylesheet" type="text/css" href="style/style.css" />-->
  <style>
	  	html
	{ height: 100%;}
	
	*
	{ margin: 0;
	font-family:"微软雅黑"；
	  padding: 0;}
	
	body
	{ font: normal .80em 'trebuchet ms', arial, sans-serif;
	  background: #00899f url(pattern.png) repeat fixed;
	  color: #5d5d5d;}
	
	p
	{ padding: 0 0 15px 0;
	  line-height: 1.5em;}
	
	img
	{ border: 0;}
	
	h1, h2, h3, h4, h5, h6 
	{ font: normal 175% 'century gothic', arial, sans-serif;
	  color: #43423F;
	  margin: 0 0 15px 0;
	  padding: 5px 0 5px 0;}
	
	h2
	{ font: normal 175% 'century gothic', arial, sans-serif;
	  color: #B60000;
	  padding: 15px 0 5px 0;}
	
	h3
	{ font: normal 165% 'century gothic', arial, sans-serif;}
	
	h4, h5, h6
	{ margin: 0;
	  padding: 0 0 5px 0;
	  font: normal 120% arial, sans-serif;
	  color: #B60000;}
	
	h5, h6
	{ font: italic 95% arial, sans-serif;
	  color: #888;}
	
	h6
	{ color: #362C20;}
	
	a, a:hover
	{ background: transparent;
	  outline: none;
	  text-decoration: underline;
	  color: #51A9FB;}
	
	a:hover
	{ text-decoration: none;
	  color: #5D5D5D;}
	
	ul
	{ margin: 2px 0 22px 17px;}
	
	ul li
	{ list-style-type: circle;
	  margin: 0 0 6px 0; 
	  padding: 0 0 4px 5px;}
	
	ol
	{ margin: 8px 0 22px 20px;}
	
	ol li
	{ margin: 0 0 11px 0;}
	
	.left
	{ float: left;
	  width: auto;
	  margin-right: 10px;}
	
	.right
	{ float: right; 
	  width: auto;
	  margin-left: 10px;}
	
	.center
	{ display: block;
	  text-align: center;
	  margin: 20px auto;}
	
	#main, #header, #logo, #menubar, #site_content, #footer
	{ margin-left: auto; 
	  margin-right: auto;}
	
	#main
	{ width: 950px;
	  margin: 20px auto;}
	
	#header
	{ width: 950px;
	  height: 121px;}
	
	#logo
	{ width: 910px;
	  position: relative;
	  height: 100px;
	  background: transparent;
	  padding: 10px 0 10px 0;}
	
	#logo h1, #logo h2
	{ font: normal 300% 'century gothic', arial, sans-serif;
	  border-bottom: 0;
	  text-transform: none;
	  margin: 0 0 0 9px;}
	
	#logo_text h1, #logo_text h1 a, #logo_text h1 a:hover 
	{ padding: 0px 0 0 0;
	  color: #A8AA94;
	  letter-spacing: 0.1em;
	  text-decoration: none;}
	
	#logo_text h1 a .logo_colour
	{ color: #FFF;}
	
	#logo_text h2
	{ font-size: 120%;
	  padding: 4px 0 0 0;
	  color: #A8AA94;}
	
	#menubar
	{ height: 46px;
	  width: 950px;
	  margin: 1px auto 0 auto;
	  background: transparent url(tab.png);} 
	
	ul#menu
	{ float: left;
	  margin: 0;padding: 0;}
	
	ul#menu li
	{ float: left;
	  padding: 0 0 0 6px;
	  list-style: none;
	  margin: 0px 2px 0 0;}
	
	ul#menu li a
	{ font: normal 100% 'trebuchet ms', sans-serif;
	  display: block; 
	  float: left; 
	  height: 27px;
	  padding: 12px 28px 5px 22px;
	  text-align: center;
	  color: #FFF;
	  border-right: 1px solid #636363;
	  text-decoration: none;} 
	
	ul#menu li.tab_selected a
	{ height: 27px;
	  padding: 6px 28px 5px 22px;}
	
	ul#menu li.selected a, ul#menu li.selected a:hover
	{ color: #ECEF01;}
	
	ul#menu li a:hover
	{ color: #ECEF01;}
	
	#site_content
	{ width: 925px;
	  overflow: hidden;
	  margin: 44px auto 0 auto;
	  padding: 10px 0 0 25px;
	  background: #EEE;
	  border-top: 0;
	  border-bottom: 0;
	  color: #5D5D5D;} 
	
	#sidebar_container
	{ float: right;
	  width: 224px;
	  padding: 10px 20px 20px 0;}
	.inner_copyright{text-indent:-9999px;height:0;line-height:0;font-size:0;overflow:hidden;}
	.sidebar_top, .sidebar_base
	{ width: 222px;
	  height: 14px;
	  background: transparent url(side_top.png) no-repeat;}
	
	.sidebar_base
	{ background: url(side_base.png) no-repeat;}
	
	.sidebar
	{ float: right;
	  width: 222px;
	  padding: 0;
	  margin: 0 0 16px 0;}
	
	.sidebar_item
	{ background: #FFF;
	  padding: 0 15px;
	  width: 192px;}
	
	.sidebar_item ul
	{ width: 178px; 
	  padding: 0px 0 0 0; 
	  margin: 0px 0 0px 0;}
	
	.sidebar_item li
	{ list-style: none; 
	  padding: 0 0 6px 0;margin: 0; }
	
	.sidebar_item li a, .sidebar_item li a:hover
	{ padding: 0 0 0 35px;
	  display: block;
	  background: transparent url(link.png) no-repeat left center;} 
	
	.sidebar_item li a.selected
	{ color: #444;
	  text-decoration: none;} 
	
	#content
	{ text-align: left;
	  width: 655px;
	  padding: 15px 0 20px 0;
	  margin: 0;}
	
	#content ul
	{ margin: 2px 0 12px 0px;}
	
	#content ul li
	{ list-style-type: none;
	  background: url(bullet.png) no-repeat;
	  margin: 0 0 2px 0; 
	  padding: 0 0 4px 25px;
	  line-height: 1.5em;}
	
	#footer
	{ width: 950px;
	  font: normal 90% 'trebuchet ms',  arial, sans-serif;
	  height: 65px;
	  padding: 20px 0 5px 0;
	  text-align: center; 
	  color: #FFF;
	  background: transparent url(tab.png) repeat;}
	
	#footer p
	{ padding: 0 0 10px 0;}
	
	#footer a, #footer a:hover
	{ color: #FFF;
	  text-decoration: underline;}
	
	#footer a:hover
	{ color: #FFF;
	  text-decoration: none;}
	
	.search
	{ color: #5D5D5D; 
	  border: 1px solid #BBB; 
	  width: 134px; 
	  padding: 4px; 
	  font: 100% arial, sans-serif;}
	
	.form_settings
	{ margin: 15px 0 0 0;}
	
	.form_settings p
	{ padding: 0 0 4px 0;}
	
	.form_settings span
	{ float: left; 
	  width: 200px; 
	  text-align: left;}
	  
	.form_settings input, .form_settings textarea
	{ padding: 5px; 
	  width: 299px; 
	  font: 100% arial; 
	  border: 1px solid #E5E5DB; 
	  background: #FFF; 
	  color: #47433F;}
	  
	.form_settings .submit
	{ font: 100% arial; 
	  border: 1px solid; 
	  width: 99px; 
	  margin: 0 0 0 212px; 
	  height: 33px;
	  padding: 2px 0 3px 0;
	  cursor: pointer; 
	  background: #3B3B3B; 
	  color: #FFF;}
	
	.form_settings textarea, .form_settings select
	{ font: 100% arial; 
	  width: 299px;}
	
	.form_settings select
	{ width: 310px;}
	
	.form_settings .checkbox
	{ margin: 4px 0; 
	  padding: 0; 
	  width: 14px;
	  border: 0;
	  background: none;}
	
	.separator
	{ width: 100%;
	  height: 0;
	  border-top: 1px solid #D9D5CF;
	  border-bottom: 1px solid #FFF;
	  margin: 0 0 20px 0;}
	  
	table
	{ margin: 10px 0 30px 0;}
	
	table tr th, table tr td
	{ background: #3B3B3B;
	  color: #FFF;
	  padding: 7px 4px;
	  text-align: left;}
	  
	table tr td
	{ background: #DDD;
	  color: #47433F;
	  border-top: 1px solid #FFF;}
  </style>
</head>

<body>
  <div id="main">
    <div id="header">
      <div id="logo">
        <div id="logo_text">
          <!-- class="logo_colour", allows you to change the colour of the text -->
<!--           <h1><a href="index-1.html">Blog-GY2017</a></h1> -->
          <h2>前进的路途中不止你一人 | 何不让优秀贯穿一生</h2>
        </div>
      </div>
      <div id="menubar">
        <ul id="menu">
          <!-- put class="selected" in the li tag for the selected page - to highlight which page you're on -->
          <li><a href="index-1.html">Home</a></li>
          <li class="selected"><a href="#">Examples</a></li>
          <li><a href="#">A Page</a></li>
          <li><a href="#">Another Page</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
    </div>
    <div id="site_content">
      <div id="sidebar_container">
        <div class="sidebar">
          <div class="sidebar_top"></div>
          <div class="sidebar_item">
            <!-- insert your sidebar items here -->
            <h3>前端生涯</h3>
            <h4>生涯新秀</h4>
            <h5>June 6th, 2016</h5>
            <p>2016年6月6日加入前端这个行业...&nbsp;<a href="#">更多</a></p>
          </div>
          <div class="sidebar_base"></div>
        </div>
        <div class="sidebar">
          <div class="sidebar_top"></div>
          <div class="sidebar_item">
            <h3>人家是个广告位啦</h3>
            <ul>
              <li><a href="#">link 1</a></li>
              <li><a href="#">link 2</a></li>
              <li><a href="#">link 3</a></li>
              <li><a href="#">link 4</a></li>
            </ul>
          </div>
          <div class="sidebar_base"></div>
        </div>
        <div class="sidebar">
          <div class="sidebar_top"></div>
          <div class="sidebar_item">
            <h3>Search</h3>
            <form method="post" action="#" id="search_form">
              <p>
                <input class="search" type="text" name="search_field" value="Enter keywords....." />
                <input name="search" type="image" style="border: 0; margin: 0 0 -9px 5px;" src="style/search.png" alt="Search" title="Search" />
              </p>
            </form>
          </div>
          <div class="sidebar_base"></div>
        </div>
      </div>
      <div id="content">
        <!-- insert the page content here -->
        <h1>例子</h1>
        <p>此页面包含作为此设计一部分可用的所有样式元素的示例。使用此页面作为参考，同时您构建您的网站。</p>
        <h2>标题</h2>
        <p>这些是不同的标题格式:</p>
        <h1>标题 1</h1>
        <h2>标题 2</h2>
        <h3>标题 3</h3>
        <h4>标题 4</h4>
        <h5>标题 5</h5>
        <h6>标题 6</h6>
        <h2>文本</h2>
        <p>以下示例显示文本 (within '&lt;p&gt;&lt;/p&gt;' tags) 将如何显示：</p>
        <p><strong>这是一个粗体文本的例子</strong></p>
        <p><i>这是斜体文字的一个例子</i></p>
        <p><a href="#">这是一个超链接</a></p> 
        <h2>清单</h2>	<!--修改到这里标记一下-->
        <p>这是一个无序的列表:</p>
        <ul>
          <li>项目 1</li>
          <li>项目2</li>
          <li>项目 3</li>
          <li>项目 4</li>
        </ul>
        <p>这是一个有序的列表:</p>
        <ol>
          <li>项目 1</li>
          <li>项目 2</li>
          <li>项目 3</li>
          <li>项目 4</li>
        </ol>
        <h2>图片</h2>
        <p>图像可以放置在左侧，中央或右侧:</p>
        <span class="left"><img src="style/graphic.png" alt="example graphic" /></span>
        <p>
					我是可爱的图片说明~
        </p>
        <span class="center"><img src="style/graphic.png" alt="example graphic" /></span>
        <span class="right"><img src="style/graphic.png" alt="example graphic" /></span>
        <p>
					我是可爱的图片说明~
					<br />
					<br />
					<br />
					<br />
        </p>
        <h2>表格</h2>
        <p>表格应用于显示数据，不用于布局您的网站:</p>
        <table style="width:100%; border-spacing:0;">
          <tr><th>项目</th><th>描述</th></tr>
          <tr><td>项目 1</td><td>项目说明 1</td></tr>
          <tr><td>项目 2</td><td>项目说明 2</td></tr>
          <tr><td>项目 3</td><td>项目说明 3</td></tr>
          <tr><td>项目 4</td><td>项目说明 4</td></tr>
        </table>
        <h2>表单</h2>
        <form action="#" method="post">
          <div class="form_settings">
            <p><span>表单字段示例</span><input type="text" name="name" value="" /></p>
            <p><span>Textarea示例</span><textarea rows="8" cols="50" name="name"></textarea></p>
            <p><span>复选框示例</span><input class="checkbox" type="checkbox" name="name" value="" /></p>
            <p><span>下拉列表示例</span><select id="id" name="name"><option value="1">Example 1</option><option value="2">Example 2</option></select></p>
            <p style="padding-top: 15px"><span>&nbsp;</span><input class="submit" type="submit" name="name" value="button" /></p>
          </div>
        </form>
      </div>
    </div>
    <div id="footer">
      <p><a href="index-1.html">Home</a> | <a href="#">Examples</a> | <a href="#">A Page</a> | <a href="#">Another Page</a> | <a href="#">Contact</a></p>
      <p>Copyright &copy; Blog-GY2017 
<!--     </div> -->
    <p>&nbsp;</p>
<!--   </div> -->
<!-- </body>
</html> -->
