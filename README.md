# Fullpage
## 一、链入所需文件
```
<!-- 导入jquery文件 -->
  <script src="./jquery/jquery-3.6.0.min.js"></script>
<!-- 导入fullpage文件 -->
  <link rel="stylesheet" href="./fullPage.js/src/csfullpage.css">
  <script src="./fullPage.js/vendors/easings.min.js">script>
  <script src="./fullPage.js/dist/fullpage.js"></script>
```
## 二、HTML 默认代码
```
<!-- 默认情况下，每一屏幕的代码都需要有DIV包裹，并且设置DIV的类名为section，默认情况下，第一个section将作为首页显示在页面上 -->
  <div id="fullpage">
      <div class="section activ">Some section</div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
      <div class="section fp-auto-height">
          <div class="foot-in">
                
          </div>
      </div>
  </div>
```
## 三、JS 初始化代码
```
 $(function(){
	$('#fullpage').fullpage({
		sectionsColor: ['#1bbc9b', '#4BBFC3', '#7BAABE', '#f90']
	});
});
```