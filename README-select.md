# input-select

用户选项输入

## Attributes

* `name`
* `multi`: 是否多选
* `flatten`: 是否把选项展开显示为 `radio` 或 `checkbox`，默认选项少于等于3个时会自动展开
* `label`: 可以为空
* `value`

## Example

```html
<z-input-select flatten="false" label="Gender" value="">
  <z-datalist ...>
    <option name="male">Male</option>
    <option name="female">Female</option>
  </z-datalist>
  <p>description</p>
  <z-tooltip attach="parent" side="right">...</z-tooltip>
</z-input-select>
```
