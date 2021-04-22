# vue-manage-system

### 项目说明： 

一个电商后台管理系统

### 项目技术栈：

+ vue-cli
+ vue-router
+ vuex
+ axios
+ element-ui
+ echarts
+ nprogress
+ less
+ eslint
+ babel
+ ...

### 项目功能：

- [x] 登录/退出
- [x] 用户管理
- [x] 添加用户
- [x] 修改用户
- [x] 删除用户
- [x] 权限管理
- [x] 添加角色
- [x] 修改角色
- [x] 删除角色
- [x] 分配权限
- [x] 商品管理
- [x] 添加商品
- [x] 修改商品
- [x] 删除商品
- [x] 添加分类
- [x] 修改分类
- [x] 删除分类
- [x] 订单管理
- [x] 搜索订单
- [x] 修改订单
- [x] 查询物流
- [x] 数据统计
- [x] 图表展示
- [x] 侧边栏伸展/收缩
- [x] ...

### 项目结构：

```a
│  .browserslistrc
│  .editorconfig
│  .eslintrc.js
│  .gitignore
│  .prettierrc
│  babel.config.js
│  package-lock.json
│  package.json
│  README.md
│  vue.config.js         
│  
├─dist                                // 打包的数据文件              
│  │  favicon.ico
│  │  index.html
│  │  
│  ├─css
│  │      app.0ac37030.css
│  │      Cate_Params.ced0d151.css
│  │      GoodsList_Add.c34accc1.css
│  │      login_home_welcome.baeb7995.css
│  │      Order_Report.e9b73ea1.css
│  │      Users_Rights_Roles.dc2a0135.css
│  │      
│  ├─img
│  │      heima.b5a855ee.png
│  │      iconfont.f6026e89.svg
│  │      logo.82b9c7a5.png
│  │      
│  └─js
│          app.25b6f2a1.js
│          app.25b6f2a1.js.map
│          Cate_Params.ac28b826.js
│          Cate_Params.ac28b826.js.map
│          Cate_Params~GoodsList_Add~Users_Rights_Roles.126a2a11.js
│          Cate_Params~GoodsList_Add~Users_Rights_Roles.126a2a11.js.map
│          chunk-vendors.c485d4a0.js
│          chunk-vendors.c485d4a0.js.map
│          GoodsList_Add.53a8d4cc.js
│          GoodsList_Add.53a8d4cc.js.map
│          login_home_welcome.78276de6.js
│          login_home_welcome.78276de6.js.map
│          Order_Report.9b8093c6.js
│          Order_Report.9b8093c6.js.map
│          Users_Rights_Roles.1dea101a.js
│          Users_Rights_Roles.1dea101a.js.map
│          
├─public
│      favicon.ico
│      index.html
│      
└─src
    │  App.vue                         // 入口Vue文件  
    │  main-dev.js                     // 入口js文件（开发模式）
    │  main-prod.js                    // 入口js文件（生产模式）
    │  router.js                       // 路由
    │  
    ├─assets                           // 图片等静态资源文件
    │  │  heima.png
    │  │  logo.png
    │  │  
    │  ├─css
    │  │      global.css
    │  │      
    │  └─fonts
    │          demo.css
    │          demo_fontclass.html
    │          demo_symbol.html
    │          demo_unicode.html
    │          iconfont.css
    │          iconfont.eot
    │          iconfont.js
    │          iconfont.svg
    │          iconfont.ttf
    │          iconfont.woff
    │          
    ├─components
    │  │  Home.vue                        // 主页面组件
    │  │  Login.vue                       // 登录页面组件      
    │  │  Welcome.vue                     // 欢迎页面组件                     
    │  │  
    │  ├─goods                            
    │  │      Add.vue                     // 添加商品组件               
    │  │      Cate.vue                    // 商品分类组件
    │  │      List.vue                    // 商品列表组件
    │  │      Params.vue                  // 分类参数组件
    │  │      
    │  ├─order                                           
    │  │      citydata.js                 // 城市数据文件
    │  │      Order.vue                   // 订单列表组件
    │  │      
    │  ├─power                            
    │  │      Rights.vue                  // 角色列表组件
    │  │      Roles.vue                   // 权限列表组件
    │  │      
    │  ├─report                           
    │  │      Report.vue                  // 数据报表组件
    │  │      
    │  └─user                             
    │          Users.vue                  // 用户列表组件
    │          
    └─plugins
        │  element.js                     // 导入element组件的插件
        │  
        ├─timeline                        // 时间线插件        
        │  │  index.js
        │  │  timeline.css
        │  │  
        │  └─src
        │          item.vue
        │          main.vue
        │          
        └─timeline-item                    // 时间线子项插件  
                index.js
                timeline-item.css
```

### 项目展示：

![login](https://user-images.githubusercontent.com/50788337/111029898-38274780-843a-11eb-80d9-a82095cea8b6.png)
![user](https://user-images.githubusercontent.com/50788337/111029900-3bbace80-843a-11eb-8fa8-0a7b3bd5cd26.png)
![role](https://user-images.githubusercontent.com/50788337/111029906-41181900-843a-11eb-9b59-6e7b5f8ba5a1.png)
![goods](https://user-images.githubusercontent.com/50788337/111029912-4e350800-843a-11eb-941f-6dc124e75ae5.png)
![order](https://user-images.githubusercontent.com/50788337/111029916-50976200-843a-11eb-9ba7-e8a7bbf559c1.png)
![report](https://user-images.githubusercontent.com/50788337/111029917-53925280-843a-11eb-9f3e-1008dd578f23.png)

### 项目使用：

```
1. git clone https://github.com/kevin102606/vue-manage-system
2. cd  vue-manage-system
3. npm install
4. npm run serve
```
