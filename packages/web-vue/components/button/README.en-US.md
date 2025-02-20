```yaml
meta:
  type: Component
  category: Common
title: Button
description: Button is a command component that can initiate an instant operation.
```

*Auto translate by google.*

@import ./__demo__/basic.md

@import ./__demo__/icon.md

@import ./__demo__/shape.md

@import ./__demo__/size.md

@import ./__demo__/status.md

@import ./__demo__/disabled.md

@import ./__demo__/loading.md

@import ./__demo__/long.md

@import ./__demo__/group.md


### `<button>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|type|Button types are divided into five types: secondary, primary, dashed, outline and text.|`'primary' \| 'secondary' \| 'outline' \| 'dashed' \| 'text'`|`'secondary'`|
|shape|Button shape|`'square' \| 'round' \| 'circle'`|`-`|
|status|Button state|`'normal' \| 'warning' \| 'success' \| 'danger'`|`'normal'`|
|size|Button size|`'mini' \| 'small' \| 'medium' \| 'large'`|`'medium'`|
|long|Whether the width of the button adapts to the container.|`boolean`|`false`|
|loading|Whether the button is in the loading state|`boolean`|`false`|
|disabled|Whether the button is disabled|`boolean`|`false`|
|html-type|Set the native `type` attribute of `button`, optional values refer to [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button#attr-type "_blank")|`string`|`'button'`|
|href|Set up a jump link. When this property is set, the button is rendered as `<a>`|`string`|`-`|
### `<button>` Events

|Event Name|Description|Parameters|
|---|---|---|
|click|Emitted when the button is clicked|event: `Event`|
### `<button>` Slots

|Slot Name|Description|Parameters|
|---|---|---|
|icon|Icon|-|




### `<button-group>` Props

|Attribute|Description|Type|Default|
|---|---|---|:---:|
|type|Children button types are divided into five types: secondary, primary, dashed, outline and text.|`'primary' \| 'secondary' \| 'outline' \| 'dashed' \| 'text'`|`'secondary'`|
|status|Children button state|`'normal' \| 'warning' \| 'success' \| 'danger'`|`'normal'`|
|shape|Button shape|`'square' \| 'round' \| 'circle'`|`'square'`|
|size|Children button size|`'mini' \| 'small' \| 'medium' \| 'large'`|`'medium'`|
|disabled|All children whether the button is disabled|`boolean`|`false`|


