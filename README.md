<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [FE-Problem Finishing](#fe-problem-finishing)
  - [$HTML， HTTP，web综合问题](#$html，-http，web综合问题)
    - [常见排序算法的时间复杂度,空间复杂度](#常见排序算法的时间复杂度空间复杂度)
    - A
    - A
    - A
  - [$CSS部分](#$css部分)
    - [CSS选择器有哪些](#css选择器有哪些)
    - A
    - A
    - A
  - [$Javascript 部分](#Javascript部分)
    - [严格模式和正常模式](#严格模式和正常模式)
    - [Scope作用范围](#Scope作用范围)
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
    - A
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# FE-Problem Finishing

个人收集常见或遇到的知识点、答案，参考答案仅代表个人观点，通过文档内搜索目录可快速定位

## $HTML综合问题
### 三级标题


## Javascript部分

### 严格模式和正常模式
1. 概述
　　除了正常运行模式，ECMAscript 5添加了第二种运行模式："严格模式"（strict mode）。顾名思义，这种模式使得Javascript在更严格的条件下运行。

2. 为什么用严格模式
- 消除Javascript语法的一些不合理、不严谨之处，减少一些怪异行为;
- 消除代码运行的一些不安全之处，保证代码运行的安全；
- 提高编译器效率，增加运行速度；
- 为未来新版本的Javascript做好铺垫。
　　"严格模式"体现了Javascript更合理、更安全、更严谨的发展方向，包括IE 10在内的主流浏览器，都已经支持它，许多大项目已经开始全面拥抱它。
　　另一方面，同样的代码，在"严格模式"中，可能会有不一样的运行结果；一些在"正常模式"下可以运行的语句，在"严格模式"下将不能运行。掌握这些内容，有助于更细致深入地理解Javascript，让你变成一个更好的程序员。

3. 进入标志


    "use strict";

4.如何调用

4.1针对单个脚本

    <script>
      "use strict";
      console.log("这是严格模式。");
    </script>

4.2针对单个函数

    function strict(){
      "use strict";
      return "这是严格模式。";
    }
    function notStrict() {
      return "这是正常模式。";
    }

### Scope作用范围



