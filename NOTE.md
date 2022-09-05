# 项目记录
## 1. 运行后自动打开浏览器
在package.json中`scripts`中的`serve`中添加参数` --open --host=localhost`
```javascript
  "scripts": {
    "serve": "vue-cli-service serve --open --host=localhost",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint"
  },
```
