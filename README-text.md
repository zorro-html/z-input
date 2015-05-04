# input-text

用户文本输入

## Attributes

* `name`
* `type`: `text|password`
* `multi`: 是否多行 (textarea)
* `rows`: 多行情况下的展示行数
* `label`: 可以为空
* `placeholder`
* `value`
* `valueAsNumber`: 以 `value` 为主并与其保持同步，可读写
* `valueAsDate`: 以 `value` 为主并与其保持同步，可读写

## Example

```html
<z-input-text value="" label="..." placeholder="...">
<p>description</p>
<z-validator pattern="email"></z-validator>
<z-tooltip attach="parent" side="right">...</z-tooltip>
<z-datalist ...>...</z-datalist>
</z-input-text>
