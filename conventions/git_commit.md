
# git commit 规范

## git commit日志基本规范

```doc
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

## type 类型

### 常用类型

| type     | 描述                                         |
| -------- | -------------------------------------------- |
| revert   | 回滚                                         |
| docs     | 文档修改                                     |
| fix      | 修复bug                                      |
| feat     | 新功能                                       |
| enhance  | 对现有功能的改进和完善                       |
| refactor | 代码变更或重构 (不新增功能和修复bug)         |
| style    | 代码格式或风格变更 (不改变代码逻辑和功能)    |
| build    | 构建系统或者外部依赖的改动                   |
| ci       | ci (Continuous Integration) 配置或脚本的改动 |
| release  | 发布版本                                     |
| pref     | 性能优化                                     |
| temp     | 临时提交 (需要在后续提交中一同说明)          |
| test     | 测试相关                                     |
| warn     | 警告 (通常用于警示可能出现的问题)            |
| add      | 添加文件层面的内容                           |
| move     | 移动文件层面的内容                           |
| remove   | 删除文件层面的内容                           |
| rename   | 重命名文件层面的内容                         |

## 格式要求

```doc
标题行：50个字符以内，描述主要变更内容。

主体内容：更详细的说明文本，建议72个字符以内。 需要描述的信息包括:
* 为什么这个变更是必须的? 它可能是用来修复一个bug，增加一个feature，提升性能、可靠性、稳定性等等。
* 他如何解决这个问题? 具体描述解决问题的步骤。
* 是否存在副作用、风险?

尾部：如果需要的化可以添加一个链接到issue地址或者其它文档，或者关闭某个issue。
```

# 参考资料

https://feflowjs.com/zh/guide/rule-git-commit.html
https://whlit.github.io/git/git-commit-prefix.html
