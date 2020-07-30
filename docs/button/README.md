### Button 按钮

按钮用于开始一个即时操作。

#### 何时使用

标记了一个（或封装一组）操作命令，响应用户点击行为，触发相应的业务逻辑。

#### 组件注册

```js
import { Button } from "plblib";
Vue.use(Button);
```

#### 代码演示

```js
test;
```

#### API

| 参数     | 说明         | 类型    | 默认值  | 版本 |
| -------- | ------------ | ------- | ------- | ---- |
| disabled | 按钮失效状态 | boolean | `false` |

#### 事件

| 事件名称 | 说明             | 回调参数        |
| -------- | ---------------- | --------------- |
| click    | 点击按钮时的回调 | (event) => void |