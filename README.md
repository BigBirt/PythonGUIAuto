<h2>自用自动化的GUI脚本<h2>
<br>1、使用PYQT5搭建
<br>2、可使用脚本airtest、uiautomator2
<br>3、脚本编写注释：@开头为定义变量 ##开头为用例标题，脚本代码不需要加开头，脚本文件txt即可
<br>4、执行文件为main.py , ui文件时app.ui, 其余为自定义
<br>脚本例子：
<p>
  @devices=android:///
  <br>@pn=com.neusoft.na.navigation

  <br>##用例1
  <br>d.xpath('//*[@resource-id="com.android.systemui:id/home"]').click()
</p>

