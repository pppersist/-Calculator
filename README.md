# -Calculator
html+css+jQuery

过程中出错的地方：
  1：$(".button").click写成$(".button").onclick
  2：$(this).attr("value");
     1)this不小心写成“this”，注意什么时候不加“”；
        例：$(this)当前html元素
          $(".test1") class="test1" 的元素。
          $("#test2") id="test2" 的元素。
     2)attr() 方法设置或返回被选元素的属性和值。
  3:"Ans"按钮函数的实现
     需将clear设置为false，num设为total。


if  you like it
please click "star"
