<h1 align="center">Ant Design Theme for Aliyun</h1>

<div align="center">


Ant Design theme [variables](https://github.com/lesonky/we-theme-for-antd/blob/master/index.ts) for WE-Design.

> Still being experimental, welcome to try out and help us to improve it.

</div>

## Install

```bash
$ npm install @njshaoshao/we-theme
```

## Usage

### webpack

```js
import weTheme from '@njshaoshao/we-theme';

// webpack.config.js: less-loader
{
  loader: 'less-loader',
  options: {
    modifyVars: weTheme,
  },
},
```

### umi

[https://umijs.org/config/#theme](https://umijs.org/config/#theme)

```js
import weTheme from '@njshaoshao/we-theme';

// config.js or .umirc.js
export default {
  "theme": weTheme,
}
```

> Use in Ant Design Pro: https://github.com/ant-design/ant-design-pro/pull/2946/

### less

```less
@import "~@njshaoshao/we-theme/index.less";
```
