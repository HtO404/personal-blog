# personal-blog

如从的个人博客网站 — 测试开发工程师的个人主页与技术作品集

## 技术栈

- **框架**: [Astro](https://astro.build) - 静态站点生成器
- **UI**: [Tailwind CSS](https://tailwindcss.com)
- **部署**: [Netlify](https://netlify.com) - 免费静态托管

## 功能

- 💫 3D 轨道动画环绕气泡（展示测试开发技能栈）
- 🎯 无限滚动技术亮点卡片
- 📅 工作经历时间线
- 📊 技能进度条与标签云
- 🎨 全页面马赛克水波纹交互
- 📱 完全响应式设计
- 🔄 滚动视差动画

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 预览构建结果
npm run preview
```

## 项目结构

```
personal-blog/
├── content/           # 个人资料（JSON 格式）
│   ├── profile.json   # 基本信息
│   ├── experience.json # 工作经历
│   ├── skills.json    # 技能列表
│   └── projects.json  # 项目作品
├── src/
│   ├── components/    # UI 组件 (Hero, Influencer, Experience, Skills, Projects 等)
│   ├── layouts/       # 页面布局
│   └── pages/         # 页面路由
├── public/            # 静态资源
├── .gitignore
└── package.json
```

## 内容维护

编辑 `content/` 目录下的 JSON 文件即可更新个人资料。