# 一级标题
## 二级标题


**粗体文本**
*斜体文本*  

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")  

<img decoding="async" src="http://static.runoob.com/images/runoob-logo.png" width="50%">  

```html
<div id="app">
  {{ message }}
</div>
```

```js


```

```js
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
```


```js
// wrapper function for providing a more flexible interface
// without getting yelled at by flow
export function createElement (
  context: Component,
  tag: any,
  data: any,
  children: any,
  normalizationType: any,
  alwaysNormalize: boolean
): VNode | Array<VNode> {
  if (Array.isArray(data) || isPrimitive(data)) {
    normalizationType = children
    children = data
    data = undefined
  }
  if (isTrue(alwaysNormalize)) {
    normalizationType = ALWAYS_NORMALIZE
  }
  return _createElement(context, tag, data, children, normalizationType)
}
```  


`hello`