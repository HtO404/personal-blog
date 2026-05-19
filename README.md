# personal-blog

如从的个人博客网站 - 面向面试展示技术经验与项目作品

## 技术栈

- **框架**: [Astro](https://astro.build) - 静态站点生成器
- **UI**: [React](https://react.dev) + [Tailwind CSS](https://tailwindcss.com)
- **部署**: [Netlify](https://netlify.com) - 免费静态托管

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

## 更新内容

1. 编辑 `content/` 文件夹中的 JSON 文件
2. 运行 `npm run build` 构建
3. 推送到 GitHub，Netlify 会自动部署

## 项目结构

```
personal-blog/
├── content/          # 个人资料（JSON 格式）
│   ├── profile.json  # 基本信息
│   ├── experience.json # 工作经历
│   ├── skills.json   # 技能列表
│   └── projects.json # 项目作品
├── src/
│   ├── components/   # UI 组件
│   ├── layouts/      # 页面布局
│   └── pages/        # 页面路由
├── public/           # 静态资源
└── package.json
```

## 部署到 Netlify

1. Fork 或 Clone 本仓库到你的 GitHub
2. 登录 [Netlify](https://netlify.com)
3. 点击 "Add new site" → "Import an existing project"
4. 选择你的 GitHub 仓库
5. 构建设置：
   - Build command: `npm run build`
   - Publish directory: `dist`
6. 点击 "Deploy site"

## License

MIT
