缺陷分类：
* 功能不正常
````所应提供的功能在使用上并不符合产品设计规格说明书中规定的要求，或是根本无法使用。这个错误常常会发生在测试过程的初期和中期，有许多在设计规格说明书中规定的功能无法运行，或是运行结果达不到预期设计。````

* 软件在使用上感觉不方便
````只要是不知如何使用或难以使用的软件，在产品设计上一定是出了问题需要产品人员介入优化。````

* 软件的结构未做良好规划
* 提供的功能不充分
````软件提供的功能在运作上正常，但对于使用者而言却不完整。即使软件的功能运作结果符合设计规格的要求，系统测试人员在测试结果的判断上，也必须从使用者的角度进行思考，这就是所谓的“从用户体验出发”。````

* 与软件操作者的互动不良
````一个好的软件必须与操作者之间可以实现正常互动。在操作者使用软件的过程中，软件必须很好地响应。例如在浏览网页时，如果操作者在某一网页填写信息，但是输入的信息不足或有误。当点击“确定”按钮后，网页此时提示操作者输入信息有误，却并未指出错误的哪里，操作者只好回到上一页重新填写，或直接放弃离开。这个问题就是典型的在软件对操作互动方面未做完整的设计。````

* 使用性能不佳
* 未做好错误处理
* 边界条件控制有误
* 计算错误
* 使用一段时间所产生的错误
* 控制流程的错误
* 在大数据量压力下所产生的错误
* 在不同硬件环境下产生的错误
* 版本控制不良导致的错误
* 软件文档的错误

缺陷描述：

严重程度：
* 灾难(不解决没法干活)
* 严重(不解决不能上线)
* 一般(在不影响上线进度的情况下)
* 次要(经确认本次上线可不修复)

出现频率：频繁/偶尔/无法重现

重现步骤：
1. 
2. 
3. 

代码分支：当前测试的代码来自哪个分支的哪次 commit