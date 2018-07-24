1.javascriptd介绍实现输
创建函数。对象，类的方法
1.字符串反转
function reverseString(str){
	return str.split("").reverse().join("");
}
console.log(reverseString("hellogirl!"));
2.数组去重

Array.prototype.distinct=function(){
	var i;j;len=arr.length;newArr=[];
	for(i=0;i<len;i++){
		for(j=0;k=j<len;j++){
			if(arr[i]===arr[j]){
			j=i++;
			}
		}
		newArr.push(arr[i]);
	}
	return newArr;
}
var arr=[1,3,2,4,,5,6,4,3,1,1,2,];
console.log(arr.distinct());
数据类型--字符串--数组--对象--条件判断--循环
操作字符串：
1.s.length
2.toUpperCase();
3.toLowerCase()
4.indexOf()
5.substring()
数组操作
1.arr.length
2.arr.indexOf()
3.arr.slice()==s.substring
4.arr.push()
5.arr.pop()
6.arr.unshift()
7.arr.shift()
8.arr.sort()
9.arr.reverse()
10.arr.splice()万能方法

11.arr.concat()
12.arr.join()

JavaScript把null、undefined、0、NaN和空字符串''视为false，其他值一概视为true，因此上述代码条件判断的结果是true
this是一个特殊变量，它始终指向当前对象

闭包：(1)函数外部可以访问函数内部的局部变量
		(2)这些变量始终保存在内存中，不会随着函数的结束而销毁。