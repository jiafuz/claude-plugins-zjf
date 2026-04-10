# Claude Plugins by Jiafu ZHONG

个人定制的 Claude Code 插件集合。

## 插件列表

### knowledge-brain

个人第二大脑 - 智能管理飞书知识库，让 Claude 成为你的知识助手。

- **智能消化** - 扔给任何内容，自动提炼摘要存入知识库
- **自动分类** - 根据内容智能判断主题
- **预加载知识** - 会话启动时自动预加载索引
- **智能问答** - 根据问题语义按需加载知识库内容

安装：
```
/plugin install knowledge-brain@claude-plugins-zjf
```

详见 [plugins/knowledge-brain/README.md](plugins/knowledge-brain/README.md)

## 安装插件库

将此插件库添加到 Claude Code：

```
/plugin marketplace add /home/jiafu/Projects/Others/claude-plugins-zjf
```

## 插件结构

每个插件遵循标准结构：

```
plugin-name/
├── .claude-plugin/
│   └── plugin.json      # 插件元数据（必需）
├── commands/            # 斜杠命令
├── skills/              # Skill 定义
├── hooks/               # 钩子脚本
└── README.md            # 文档
```

## 作者

Jiafu ZHONG (jiafu.zhong@uih.cn)