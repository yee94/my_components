# 这是什么？

在vue的社区中有很多关于vue的组件库 ，每次查找或者使用只是使用部分样式和组件

每次引用或者安装包很是不方便 于是想直接做一个自己的组件库


# 包含样式

- Elementui
  - [message](http://element.eleme.io/#/zh-CN/component/message)
  - [Notification](http://element.eleme.io/#/zh-CN/component/notification)
  - [Card](http://element.eleme.io/#/zh-CN/component/card)
  - [Loading](http://element.eleme.io/#/zh-CN/component/loading)
- iView
  - [Alert](https://www.iviewui.com/components/alert)
  - [Switch](https://www.iviewui.com/components/switch)
  - [LoadingBar](https://www.iviewui.com/components/loading-bar)
- Muse-ui
  - [DatePicker](http://www.muse-ui.org/#/datePicker)
  - [Divider](http://www.muse-ui.org/#/divider)
  - [Checkbox](http://www.muse-ui.org/#/checkbox)
  - [Radio](http://www.muse-ui.org/#/radio)
  - [TimePicker](http://www.muse-ui.org/#/timePicker)
  - [TextField](http://www.muse-ui.org/#/textField)
- Material vue
  - [button](https://vuematerial.github.io/#/components/button)  
  - [Card](https://vuematerial.github.io/#/components/card)
  - [Dialog/Modal](https://vuematerial.github.io/#/components/dialog)
  - [File](https://vuematerial.github.io/#/components/file)
  - [List](https://vuematerial.github.io/#/components/list)

# 使用
先下载到项目中
```
git clone https://github.com/xiaobebe/my_components.git
```
在vue中引用

```
/*比如这里引用Material中的Card*/

import md-card from "src/material/mdButton"

```

在vue中使用

```
<md-card>
  <md-card-header>
    <md-card-header-text>
      <div class="md-title">Title goes here</div>
      <div class="md-subhead">Subtitle here</div>
    </md-card-header-text>

    <md-card-media>
      <img src="assets/avatar-2.jpg" alt="People">
    </md-card-media>
  </md-card-header>

  <md-card-actions>
    <md-button>Action</md-button>
    <md-button>Action</md-button>
  </md-card-actions>
</md-card>
```
