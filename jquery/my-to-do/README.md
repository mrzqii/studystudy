#### 其实是使用jquery来开发一个todo的应用 ，然后根据他的思路自己做了改进，改成自己喜欢的功能 
基本思路：  
1. 先把样式写好
2. 添加任务：通过获取的内容，把储存在一个数组里面，数组的每一项是一个对象，里面包含了每一条提醒的所有内容
3. 把这个数组通过loaclstorage保存下来
4. 每次渲染任务的时候就从本地储存里面读取这个数组，然后把渲染出来
5. 里面涉及到了是否添加备注消息，是否为已完成，这些都通过向每一个自己的对象里面添加属性来标示
6. 使用了Sortable这个插件也就是拖拽的插件，每次拖拽的完成的时候出发了onEnd事件，然后对数组进行重新排序，以便保持拖拽交换后的位置
7. 里面的一些小细节：  
8. 如何自定义checkbox框的样式  
9. 如何利用时间冒泡机制对事件进行代理  
10. 以及这样做的好处  
11. datetimepicker的使用
  

[在线演示：](https://mrzqii.github.io/study-use-jquery/jquery/my-to-do/)
