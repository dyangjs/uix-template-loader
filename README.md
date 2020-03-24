## Web Precompile Code

## Install
```shell
npm i uix-template-loader -D
```
```javascript
//webpack config
module.exports = {
    module: {
        rules: [
            {
                test: /\.(jsx|tsx|js|ts|vue)$/,
                loader: "uix-template-loader"
            }
        ]
    }
}
/** Example **/
<div>{{'<% 显示文字 %>'}}</div>
```