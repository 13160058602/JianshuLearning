//创建虚拟dom元素
//参数1：创建的元素的类型，字符串，表示元素的名称
//参数2：是一个对象或null，表示当前这个dom元素的属性
//参数3：子节点（包括其他虚拟dom获取文本子节点）
//参数n：其他子节点

//Babel把语句转换成React.createElement形式

//使用ReactDom把虚拟dom渲染到页面上
//参数1：要渲染的那个虚拟dom元素
//参数2：指定页面上一个容器

使用create-react-app脚手架工具，推荐npx create-react-app app-name，具体见https://create-react-app.dev/docs/getting-started/，
解决只有一个全局命令的问题

安装生成项目，node v14.2.0, npx v6.14.5, 会在package.json文件中生成react-scripts3.4.1依赖，应该有版本冲突，要改成react-scripts2.1.8
（需要花时间去学习一下底层原因）

一般 React Component 撰写的主要两种方式：
1、使用 ES6 的 Class（可以进行比较复杂的操作和组件生命周期的控制，相对于 stateless components 耗费资源）
//注意组件开头第一个字母都要大写
2、使用 Funtional Component 写法（单纯地 render UI 的 stateless components，没有内部状态、没有实作物件和 ref，没有生命周期函数。
若非需要控制生命周期的话，建议多使用 stateless components 获得比较好的性能）
//使用 arror function 来设计 Funtional Component 让 UI 设计更单纯（f(D) => UI），减少副作用（side effect）

Component PropType 错误校对机制
在 React 设计时除了提供 props 预设值设定（Default Prop Values）外，也提供了 Prop 的验证（Validation）机制，让整个 Component 设计更加稳健

Redux 设计和使用三原则：
1、store 是唯一的
2、只有store 能够改变自己的内容
3、Reducer 必须是纯函数

//iconfont.cn 阿里的图标网站，创建图标仓库
Redux-thunk： dispatch 返回的不再局限于对象，也可以是函数
Reducx-saga： 把异步代码拆成单独文件，可以代替redux-thunk
styled-components: 管理项目样式，代替引入样式文件,解决样式冲突问题
//styled-components 4.x版本将原来的injectGlobal方法用createGlobalStyle替换了
react-transition-group: 动画
Redux: 数据框架
React-redux: 在react中使用redux
redux-devtools-extension: 浏览器调试工具，查看数据


