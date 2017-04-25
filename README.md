<p align="center"><a href="https://vuejs.org" target="_blank"><img width="100" src="https://vuejs.org/images/logo.png"></a></p>

## 概要：使用vue做的一个购物车页面

+ 说明：不依赖构建工具，在服务环境下打开可直接看，使用vue-resource插件做数据请求，页面根据请求的数据v-for渲染出来。代码中夹杂了一点ES2015(ES6)的语法。

### 技术要素：

  1. global event bus
  2. 全局component、局部components
  3. vuex一个简单的使用示例
  4. vue生命周期钩子（一些给开发者自由发挥的回调函数。适用范围：所有vue组件、子组件、实例）

     * beforeCreate 实例创建之前
     * created      实例创建完成
     * beforeMount  搭建dom结构之前
     * mounted      页面dom搭建结束
     * beforeDestroy   摧毁vue实例之前
     * destroyed    摧毁vue实例之后
     * beforeUpdate  更新数据之前
     * updated      更新数据之后
  5. 父子组件动态传数据（根据官方建议，不在子组件中直接修改父组件变量）
  6. 通过全局api:
     * $children：从父组件获取子组件
     * $parent：在子组件中获取父组件
     * $root：获取根组件
