# 2021-campus-recruitment

2021-阿里云业务中台团队校招

## 人员

* 负责人: @云北 @枫余

## 日常

1. 根据每个同学的特点布置一些小任务，分别抽时间完成

2. 代码检查
  * 编辑器要支持 editorconfig 和 eslint (建议使用 vscode)
  * 在 webpack 编译期, 如果 eslint 有 error/warning 可以直接在控制台看到
  * eslint 规则统一的 `eslint-config-airbnb`
  * 任何 commit 的代码不能有 eslint error, 理论上也不可以有 warning, 如有大量需修改的 error/warning 可以使用 `eslint --autofix`, 也可以在 warning 处 `// eslint-disable-next-line [no-console]`

3. GitFlow
  * 长期存在有1个分支 `master`
  * 开发时应当从 `master` 分支 `checkout` 出新分支, 命名例如: `feature/some-feature` 或者 `fixbug/some-bug` 单词以中划线连接命名, 并且已 scope 开头, 参考: [Git 分支管理策略](http://www.ruanyifeng.com/blog/2012/07/git.html)
  * 不可以直接向 `master` 直接提交代码, 开发分支在开发完成后向 `develop` 分支提交 `Merge Request`, 由 @云北、@逸翾 review 后可合并
  * 注意 git commit message 的规范性

## 其他
  * 完成后可以发起mr assignee
