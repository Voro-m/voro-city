1.下载voro-city.js文件<br>
2.页面内元素格式：<br>
![image](http://seaweedman.store/images/aooe.png)<br>
3.页面内引入voro-city.js以及添加js代码(body内最好添加在元素下)
![image](http://seaweedman.store/images/aood.png)<br>
4.获取选中参数<br>
==s_province：省级==<br>
==s_city：市级==<br>
==s_county：区、自治县==<br>
1. jQuery获取参数<br>
$('#s_province option:selected').val()<br>
$('#s_city option:selected').val()<br>
$('#s_county option:selected').val()
1. js获取参数<br>
var oSprovince = document.getElementById('s_province');<br>
var oScity = document.getElementById('s_city');<br>
var oScounty = document.getElementById('s_county');<br><br>
获取oSprovince选中的参数<br>
var province_val = oSprovince.options[sel.selectedIndex].value;<br>
获取oScity选中的参数<br>
var city_val = oScity.options[sel.selectedIndex].value;<br>
获取oScounty选中的参数<br>
var county_val = oScity.options[sel.selectedIndex].value;<br>