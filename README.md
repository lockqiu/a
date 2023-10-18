# a

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### husky使用总结
操作步骤 (https://zhuanlan.zhihu.com/p/366786798)删除pre-commit 文件
安装 commitlint 工具和规则集     npm install --save-dev @commitlint/cli @commitlint/config-conventional
在 根目录下新建的 commitlint.config.js 文件中配置 （https://blog.csdn.net/ASIYAas/article/details/125717507）
提交规范示例 ： git commit -m 'feat: 新功能'  （注意空格）