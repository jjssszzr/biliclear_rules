# biliclear_rules
这是biliclear的一些规则，感兴趣的可以下载使用
## 关于测试版与稳定版
+ 测试版一般会以“rules_beta”开头，其规则较新，但误报可能性大，有概率被封
+ 稳定版一般会以“rules_stable”开头，其规则较测试版较少，更新较慢，但误报可能性小
## 如何制作 🤝
- **过滤规则：**
  过滤规则在 `rules.txt` 文件中，每一行为一个 Python 表达式，只要有任何一个匹配即判定为违规。
  - 变量：`text`，评论内容，类型为 `str`
  - 表达式中不能使用 `eval`、`exec` 等函数
  - 可使用正则表达式，默认导入 `re` 模块

## 声明 ⚠️
使用 `BiliClear` 造成的任何不良后果由使用者自行承担，开发者不承担任何责任。请谨慎使用。
使用本仓库任何规则造成的任何不良后果由使用者自行承担，开发者不承担任何责任。请谨慎使用。