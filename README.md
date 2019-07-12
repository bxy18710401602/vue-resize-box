# vue-resize-box

## 使用方法1
### 导入组件： import ResizeBox from 'vue-resize-box/src/main.vue'
### 注册组件：components: {[ResizeBox.name]: ResizeBox}
### 使用组件：\<ResizeBox/\>xxx\</ResizeBox\>

## 使用方法2
### npm install vue-resize-box
### 导入组件：import ResizeBox from 'vue-resize-box'
### 注册组件：Vue.use(ResizeBox)
### 使用组件：\<ResizeBox/\>xxx\</ResizeBox\>

## Attributes
### | 参数 | 说明 | 类型 | 可选值 | 默认值 |
### | min | 最小宽高 | object | width、height | 不限制 |
### | max | 最大宽高 | object | width、height | 不限制 |
### | move | 移动手柄配置 | object | t、l、r、b、tl、tr、bl、br | 全为true，即全可用 |
### | speed | 移动速度倍数配置 | number | 大于等于1 | 2 |
### | disabled | 是否禁用 | object | true/false | false |
