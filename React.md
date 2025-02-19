# React

### 零碎知识点

- React组件必须以大写字母开头 
- HTML标签必须小写字母
- JSX必须闭合标签 
  - 包裹到一个共享的父级中
  - 如<>...</>
- className =》 class
- {} =》 变量？ 

## 官网学习

### 描述UI

-  `<section>` 是 HTML5 引入的语义化标签，用于定义页面中的独立内容区块

- `<article>` 表示这篇文章

- **React 组件是一段可以 使用标签进行扩展 的 JavaScript 函数**

- **组件的名称必须以大写字母开头**

- return () =》 ()包裹内容  或者 return 独自一行

- 组件内嵌套定义组件会有bug + 很慢

- ![image-20250219171738695](D:\study\studyNote\React.assets\image-20250219171738695.png)

- 为什么多个 JSX 标签需要被一个父元素或者 Fragment包裹？

  - JSX底层被转化为了js对象，**不能再一个函数中返回对哦个对象**，触发用数组将他们包装起来

- 双大括号 =》 传递对象

- 解构

- children => 类似插槽？ 

  - ![image-20250219181013231](D:\study\studyNote\React.assets\image-20250219181013231.png)

- `<del>` 删除线

- 数字不能放在 && 左侧

  - 左侧为0 =》 渲染0

- 多用对象来渲染参数 

  - ```jsx
     tea: {
        part: 'leaf',
        caffeine: '15–70 mg/cup',
        age: '4,000+ years'
      },
      coffee: {
        part: 'bean',
        caffeine: '80–185 mg/cup',
        age: '1,000+ years'
      }
    ```

- 

