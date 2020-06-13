//2.创建虚拟dom元素
//参数1：创建的元素的类型，字符串，表示元素的名称
//参数2：是一个对象或null，表示当前这个dom元素的属性
//参数3：子节点（包括其他虚拟dom获取文本子节点）
//参数n：其他子节点

//Babel把语句转换成React.createElement形式

//3.使用ReactDom把虚拟dom渲染到页面上
//参数1：要渲染的那个虚拟dom元素
//参数2：指定页面上一个容器

使用create-react-app脚手架工具，推荐npx create-react-app app-name，具体见https://create-react-app.dev/docs/getting-started/，
解决只有一个全局命令的问题

安装生成项目，node v14.2.0, npx v6.14.5, 会在package.json文件中生成react-scripts3.4.1依赖，应该有版本冲突，要改成react-scripts2.1.8
（需要花时间去学习一下底层原因）
