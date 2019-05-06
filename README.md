# leetcode-practice
在学习算法的过程中记录，日积月累，提高算法相关能力😄

<div align=center>
<img src="resouce/arithmetic_logo.jpeg" width = "70%" height = "70%"/>
</div>

#### 算法题整理

****

<table align="center" border="1" cellspacing="0" width="100%">
	<tr>
		<td width="20%" height=30px  rowspan="2" bgcolor=#dddddd>数据去重</td>
      	<td height=30px>输出字符串中的第一个不重复的字符。</br>
      例如：“hello”输出 ‘h’ ，	“abbac”输出 ‘c’ ，“abdabe”输出 ‘d’
   		</br><a align="center" href="code\1001-输出字符串中第一个不重复的字符.md">参考答案<img src="resouce/icon_guide.png" width = "20" height = "20" style="margin: 0 auto"></a></td>
   </tr>
   <tr>
      	<td height=30px><a href="code\1002-有序int[]去重.md">对有序int[]去重，并输出去重后的长度，并打印出来，要求时间复杂度为O(n)，空间复杂度为O(1)。</br>
      	例如：int[] array = {-1,0,0,2,4,4,4,6};</br>
      	返回长度为：5，打印结果为：-1，0，2，4，6
		</a></td>
   </tr> 
   


   <tr>
		<td width="20%" height=30px  rowspan="3" bgcolor=#dddddd>数据查询</td>
      	<td height=30px><a href="code\2001-返回满足求和的数据索引.md">查询int[]中满足两个数据相加等于指定数值的索引，相同索引不能使用两次。</br>
      	例如：已知int[] nums = [3, 5, 7,11, 15], target = 10，返回符合条件的索引。</br>
      	nums[0] + nums[2] = 3 + 7 = 10,nums[1]+nums[1]=10;因为nums相同索引只能使用一次，所以返回[0, 1]
   		</a></td>
   </tr>
   <tr>
      	<td height=30px><a href="code\2002-返回字符串数组中，相同部分的字符串.md">查询String[]中以相同部分开始的的字符串。</br>
      	例如：["flower","flow","flight"] 返回：fl；["dog","racecar","car"] 返回：“”
   		</a></td>
   </tr>
   <tr>
      	<td height=30px><a href="code\2003-判断int数组中最多改变一个数后是否是非递增数组.md">给定一个长度为n的int数组，判断最多修改一个数据后，该数组是否为非递增数组。</br>
      	例如：[3，4，2，3] 返回：false；[3,6,4,5] 返回：true；[4,2,3] 返回true；
   		</a></td>
   </tr>

   
   
   
   <tr>
		<td width="20%" height=30px  rowspan="2" bgcolor=#dddddd>数据反转</td>
      	<td height=30px><a href="code\3001-int数据反转.md">对int类型的数据进行反转。</br>
      	例如：已知int num = 123,结果为321，如果超出范围返回0
	   	</a></td>
   </tr>
   <tr>
      	<td height=30px><a href="code\3002-判断是否是回文数据.md">判断int类型的数据是否是回文数据（反转之后是否相等）。</br>
      	例如：int num = 121,结果为true；int num = -121,结果为false；int num = 12,结果为false；
	   	</a></td>
   </tr>
   
   
   <tr>
		<td width="20%" height=30px  rowspan="1" bgcolor=#dddddd>数据转换</td>
      	<td height=30px><a href="code\4001-将罗马数字转成int数据.md">将罗马数字转成对应的int类型数据。对应关系如下：</br>
	I =>  1</br>
	V =>  5</br>
	X =>  10</br>
	L =>  50</br>
	C =>  100</br>
	D =>  500</br>
	M =>  1000</br>
      	例如：输入“III”，输出：3，输入“IV”，输出：4，输入“IX”，输出：9，输入“LVIII，输出：58(L=50,V=5,III=3)，输入“CMMXCIV”，输出：1994(M=1000,CM=900,XC=90,IV=4)</br>
      	</a></td>
   </tr>


</table>

