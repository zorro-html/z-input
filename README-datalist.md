# datalist

用户文本输入选项/提示

* 可以是`<option>`的列表
* 也可以绑定一个JavaScript数组
* (未来)可以约定某种服务端接口格式

## Attributes

* `value[{name, value, default}]`

## Events

* `change`
* `input`

## Bind ShadowRoot

* `dataupdated`

## Example

```html
<z-datalist>
  <option name="key1">Value1</option>
  <option name="key2">Value2</option>
</z-datalist>

<script>
  console.log(datalist.value);
  datalist.addEventListener('dataupdated', function () {
    console.log('updated', this.value);
  });
</script>
```
