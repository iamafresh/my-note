#1 事件传参方式
   this.handleEvent.bind(this, argument)
   
#2 善用this.props.children(react元素占位符)

#3 react 组件更新过程
   componentWillReceiveProps()
   shouldComponentUpdate()
   componentWillUpdate()
   rener()
   componentDiDMount()


#4 setState的调用是异步执行的，在调用setState之后，不要依赖this.state来立即反应新值
  更新通过props和state
  页面内容的显示方式可通过很多方式 除了props state
  和路由相关的可以通过this.props.location来判断 react-router4 NavLink的 activeStyle 正是使用了这个做判断的一个功能

#5 react 设置button disabled属性
需要通过ref


# 一些疑问
  ref 如何 获取styled包裹的input组件  这样返回的是一个组件实例  而不是一个dom