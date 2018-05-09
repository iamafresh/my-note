# 1. NavLink 激活是的样式设置（其原理大概是判断当前的location.pathname中是否包含 当前子跟路由的location.pathname
   activeClassname字符串
   activeStyle对象
   isActive行数

# 2. 非手动式的路由跳转
    this.props.history.push('/path')


# 3 重新看了react-router3 发现 4 比 3精简多了  同时有些功能也需要自己挖掘和实现
   3和vue-router更像 还有路由生命周期等  对比能更好理解

# 4 路由链接到的组件的this.props相关属性