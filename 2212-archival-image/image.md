
<table>
  <tr id="line1">
    <td>2</td> <td>2</td> <td>0</td> <td>1</td> <td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>1</td> <td>0</td>
  </tr>
  <tr id="line2">
  	<td>1</td> <td>1</td> <td>0</td> <td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>1</td> <td>0</td> <td>0</td>
  </tr>
  <tr id="line3">
 	  <td>2</td> <td>2</td> <td>0</td> <td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>0</td> <td>2</td> <td>2</td>
  </tr>
  <tr id="line4">
  	<td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>0</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td>
  </tr>
  <tr id="line5">
  	<td>1</td> <td>1</td> <td>0</td> <td>1</td> <td>1</td> <td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>1</td>
  </tr>
  <tr id="line6">
  	<td>1</td> <td>1</td> <td>0</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td> <td>1</td>
  </tr>
  <tr id="line7">
  	<td>1</td> <td>1</td> <td>0</td> <td>1</td> <td>1</td> <td>0</td> <td>1</td> <td>0</td> <td>1</td> <td>1</td>
  </tr>
  <tr id="line8">
	 <td>0</td> <td>0</td> <td>0</td> <td>1</td> <td>0</td> <td>1</td> <td>0</td> <td>0</td> <td>2</td> <td>2</td>
  </tr>
  <tr id="line9">
  	<td>1</td> <td>1</td> <td>0</td> <td>0</td> <td>1</td> <td>0</td> <td>2</td> <td>2</td> <td>0</td> <td>0</td>
  </tr>
  <tr id="line10">
  	<td>1</td> <td>1</td> <td>0</td> <td>0</td> <td>1</td> <td>0</td> <td>2</td> <td>2</td> <td>0</td> <td>0</td>
  </tr>
</table>

![SCP-2212 收容措施图像](https://github.com/iPlanC/SCP_2212_Reserch_Notes/blob/master/2212-archival-image/%E8%A7%A3%E5%AF%86.PNG?raw=true)

>0 将其标记为绿色（安全）  
>1 将其标记为黑色（不安全）  
>2 将其保持为原样  

翻找该页面HTML源码的时候发现其存在另一种解法？
``` JavaScript
    var correctMessage = "正确编辑排列已找到";
    var incorrectMessage = "错误！";
    var assumptionMessage = "侦测到不合理假设。";
```
