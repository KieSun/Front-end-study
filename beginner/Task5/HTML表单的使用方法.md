# HTML表单的使用方法

## 介绍
表单可以将获得嵌套在里面的标签的信息，并且提交给服务器

``` html
<form action="#" method="get">
```
代表使用 get 的请求方式，请求地址为 # 的服务器。

## 使用
form 中可以使用 `input`，`button`，`select`，`textarea`

### input 的使用
`input` 就是输入框，经常和 `label` 搭配使用。
`input` 中的 type 属性代表输入框的类型，`name` 代表提交表单时显示的 key，`value` 代表 key 对于的 value 值

```html
<input type="radio" id="sex" name="sex" value="women"> 女
```

### select 的使用

```html
<select name="car">
   <option>萨博</option>
   <option>萨博</option>
</select>
```

`select` 和 `option` 搭配使用，有几个 `option`，就有几个下拉框

### textarea 的使用

`textarea` 也是输入框，但是这是可以输入大量文本的输入框

```html
<textarea placeholder="ddd" rows="10" cols="40"></textarea>
```

