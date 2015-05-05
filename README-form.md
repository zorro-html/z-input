# input-form

表单结构，分为横向/纵向/平铺三种布局

## Attributes

* `[vertical]`: 纵向 (默认)
* `[oneline]`: 横向
* `[flatten]`: 平铺

## Example

```html
<z-form>
  <z-input-text name="username" label="Username"></z-input-text>
  <z-input-text name="password" type="password" label="Password"></z-input-text>
  <z-input-space label="">
    <z-btn>Login</z-btn>
  </z-input-space>
</z-form>
```
