# 02-vue-cli-v3.5.5

```
// 1. 删除原来的旧版vue-cli@2.x
yarn global remove vue-cli
// 2. 安装新版本vue-cli@3.x
yarn global add @vue/cli
// 3. 检查版本是否正确
vue --version 或者 vue -V
如果你还想用旧版本的vue init功能。可以全局安装一个 yarn global add @vue/cli-init
// 4. 在当前目录下创建一个新项目
vue create .
// 5. 输入y
? Generate project in current direction? (Y/n)
// 6. 选择 Manually select features 表示手动选择特性
? Please pick a preset:(Use arrow keys)
default (babel, eslint)
Manually select features
// 7. 按需选择
一般都会选，Babel, Router, Vuex, CSS Pre-processors, Linter / Formatter
// 8. use history mode for router? 是不是用history模式。y
// 9. 选择一种css预处理器。
Pick a CSS pre-processor。
有scss,less,stylus可供选择。
如果后期打算用ant-design-vue的话。建议用less。其实多数人也就用到个嵌套语法罢了。
// 10.选择一份代码校验和格式化的配置
推荐选择 ESLint + Standard config
// 11. 什么时候校验。可以两个都勾上。不过要是嫌影响了提交代码的效率，也可以不勾 Lint and fix on commit
// 12. 把配置文件放在哪里。放package.json里面还是放单独的文件夹中。都可以
// 13. 执行 yarn serve 跑项目
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
