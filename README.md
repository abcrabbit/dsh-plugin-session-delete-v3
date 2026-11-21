# 会话删除队列

通过可见、可取消的删除队列删除会话：已标记的会话以红色删除线显示，并在下次启动时清理。

Delete sessions through a visible, cancellable queue: marked sessions are struck through in red and removed on the next start.

## 安装

**方式一（推荐）**：在 DSH 插件的「发现」页添加索引源

```
https://raw.githubusercontent.com/abcrabbit/dsh-plugin-index/main/index.json
```

然后搜索并安装本插件。

**方式二（手动）**：下载本仓库，在 DSH「设置 → 插件 → 添加插件 → 本地目录」中选择本目录。

## 兼容性

- DSH 0.2.2 系列（在 `0.2.2-rc.5` 上验证）
- 许可证：MIT
