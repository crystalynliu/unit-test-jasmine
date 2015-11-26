**关于一些重点

---

***First

*	ES5：在多数情况下，调用提供的函数使用三个参数：**数组元素**、**元素的索引**和**数组本身**。

---

***Second

****sort() 方法用于对数组的元素进行排序。

*	语法：arrayObject.sort(sortby)；参数sortby可选。规定排序顺序。必须是函数。
	*	注：如果调用该方法时没有使用参数，将按字母顺序对数组中的元素进行排序，说得更精确点，是按照字符编码的顺序进行排序。

*	如果想按照其他标准进行排序，就需要提供比较函数，该函数要比较两个值，然后返回一个用于说明这两个值的相对顺序的数字。比较函数应该具有两个参数 a 和 b，其返回值如下：
	*	若 a 小于 b，在排序后的数组中 a 应该出现在 b 之前，则返回一个小于 0 的值。(a-b)
	*	若 a 等于 b，则返回 0。
	*	若 a 大于 b，则返回一个大于 0 的值。

---

***Third

****对象

*	一种复合值，将很多值聚合在一起，可通过名字访问这些值。
*	属性的无序集合，每个属性都是一个名/值对
*	整个对象由花括号括起来，名/值对中间用冒号分隔，名/值对之间用逗号分隔



