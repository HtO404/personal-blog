# 个人经验资料

这个文件夹用于存放你的个人经验资料，网站会根据这些资料自动更新内容。

## 文件夹结构

```
content/
├── profile.json      # 个人基本信息
├── experience.json   # 工作经历
├── skills.json       # 技能列表
├── projects.json     # 项目作品
└── assets/           # 图片等资源文件
```

## 如何更新

1. 编辑对应的 JSON 文件
2. 重新构建网站：`npm run build`
3. 推送到 GitHub，Netlify 会自动部署

## 文件格式说明

### profile.json
```json
{
  "name": "你的名字",
  "title": "你的职位",
  "bio": "个人简介",
  "location": "所在城市",
  "email": "your@email.com",
  "social": {
    "github": "https://github.com/yourusername",
    "linkedin": "https://linkedin.com/in/yourusername"
  }
}
```

### experience.json
```json
[
  {
    "company": "公司名称",
    "role": "职位",
    "period": "2022 - 至今",
    "description": "工作描述",
    "highlights": ["亮点1", "亮点2"]
  }
]
```

### skills.json
```json
[
  {
    "name": "技能名称",
    "level": 90,
    "category": "分类"
  }
]
```

### projects.json
```json
[
  {
    "title": "项目名称",
    "description": "项目描述",
    "tags": ["标签1", "标签2"],
    "link": "预览链接",
    "github": "源码链接"
  }
]
```
