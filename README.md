# lint-pre-template

## 说明

## 为什么

-   代码规范，培养写代码良好习惯
-   多人协作，方便代码管理减少 [`垃圾`] 代码
-   git 工作风格，了解什么时间什么人做什么事

## 针对自己的 Vue 项目简单定制

| Plugins     | 用途                                                                         |
| ----------- | ---------------------------------------------------------------------------- |
| eslint      | 检测代码是否符合规范，可针对团队风格在 rule 中进行定制                       |
| prettier    | 美化代码，在 `.prettierrc` 文件配置你要的风格                                |
| husky       | 管理 git 提交的钩子函数，可在"pre-commit" 中进行检测代码是否符合规范方可提交 |
| lint-staged | 对 git add 到本地暂存区的代码进行检测                                        |
| commitizen  | git 提交代码的 小工具                                                        |

## 参考链接：

[如何规范你的前端代码 2](https://juejin.cn/post/6844904048525574152)

[如何规范你的前端代码 1](https://juejin.cn/post/6976891381914533918)

## 参考链接来源于网上公开文章，请尊重他人的贡献，很感谢阅读后能得到这次实践

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```
