# react入门和组件

### 1.React课程介绍

 react特点：<br/>
  + 虚拟DOM：React也是以数据驱动的，每次数据变化React都会扫码整个虚拟DOM树，自动计算与上次虚拟DOM的差异变化，然后针对需要变化的部分进行实际的浏览器DOM更新。
  + 组件化：React可以从功能角度横向划分，将UI分解成不同组件，各组件都独立封装，整个UI是由一个个小组件构成的一个大组件，每个组件只关系自身的逻辑，彼此独立。
  + 单向数据流：React设计者认为数据双向绑定虽然便捷，但在复杂场景下副作用也是很明显，所以React更倾向于单向的数据流动-从父节点传递到子节点。（使用ReactLink也可以实现双向绑定，但不建议使用）

### 2.环境搭建和HelloWorld程序

### 3.初始JSX语法

### 4.进阶JSX语法

### 5.React组件：state成员

 注意：<br/>
   + getInitialState函数必须有返回值，可以是null,false,一个对象
   + 访问state数据的方法是"this.state.属性名"
   + 变量用{}包裹，不需要再加双引号

### 6.React组件：props和render成员

### 7.React组件：生命周期

一个组件完整的生命周期包含实例化阶段、活动阶段、销毁阶段三个阶段。

过程中涉及三个主要的动作术语：<br/>
 + mounting:表示正在挂载虚拟DOM到真实DOM
 + updating:表示正在被重新渲染
 + unmounting:表示正在将虚拟DOM移除真实DOM
 
每个动作术语提供两个函数：<br/>
 + componentWillMount()
 + componentDidMount()
 + componentWillUpdate(object nextProps, object nextState)
 + componentDidUpdate(object prevProps, object prevState)
 + componentWillUnmount()






   
   




