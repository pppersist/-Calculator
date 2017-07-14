# -Calculator（计算器）
html+css+jQuery

过程中出错的地方：</br>
  1：$(".button").click写成$(".button").onclick</br>
  2：$(this).attr("value");</br>
     1)this不小心写成“this”，注意什么时候不加“”；</br>
        例：$(this)当前html元素</br>
          $(".test1") class="test1" 的元素。</br>
          $("#test2") id="test2" 的元素。</br>
     2)attr() 方法设置或返回被选元素的属性和值。</br>
  3:"Ans"按钮函数的实现</br>
     需将clear设置为false，num设为total。</br>
</br>
</br>
if  you like it</br>
please click "star"</br>
