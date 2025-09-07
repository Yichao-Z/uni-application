# ZHANG Yichao Introduction Site

本项目为静态网站，旨在中英日双语介绍学生张一超（ZHANG Yichao），展示其学业经历、科学探索业绩、未来规划及师长评价。

## 项目结构

```
zhang-yichao-intro-site
├── src
│   ├── index.html                # 首页，张一超简介及导航
│   ├── Achievements.html         # 科学探索业绩
│   ├── Aspirations-and-Plans.html# 未来规划与学业计划
│   ├── evaluations.html          # 师长评价
│   ├── assets
│   │   └── styles.css            # 网站样式文件
│   ├── modules
│   │   ├── english
│   │   │   ├── title.txt         # 英文模块标题
│   │   │   └── content.txt       # 英文模块内容
│   │   └── japanese
│   │       ├── title.txt         # 日文模块标题
│   │       └── content.txt       # 日文模块内容
├── README.md                     # 项目说明文档
```

## 页面说明

- **index.html**  
  首页，包含张一超的中英文介绍、四个主要模块导航按钮（科学探索业绩、未来规划、师长评价），顶部弹窗可选择中英文说明，底部有联系方式和版权信息。

- **Achievements.html**  
  展示科学探索业绩，包括国家级人才培养项目经历和中学阶段科技竞赛经历。

- **Aspirations-and-Plans.html**  
  展示未来学业规划、报考日本大学理由等内容。

- **evaluations.html**  
  展示师长和教授对张一超的评价。

- **assets/styles.css**  
  网站整体配色、布局、按钮样式等均在此文件统一设置，保证所有页面风格一致。

## 部署到 GitHub Pages

1. **创建仓库**  
   在 GitHub 新建仓库（如 `uni-application`），不要初始化 README。

2. **上传项目文件**  
   在本地项目目录下执行：
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/Yichao-Z/uni-application.git
   git push -u origin main
   ```

3. **启用 GitHub Pages**  
   - 进入仓库 `Settings > Pages`
   - 选择 `main` 分支，文件夹选 `/ (root)`
   - 保存后，几分钟后可访问 `https://Yichao-Z.github.io/uni-application/`

4. **访问网站**  
   首页为 `index.html`，其它页面通过导航按钮跳转。所有配色、布局均与本地一致。

## 注意事项

- 保证所有 HTML 文件均正确引用 `assets/styles.css`，否则样式可能丢失。
- 如需修改内容或样式，直接编辑对应 HTML/CSS 文件并重新推送即可。
- 所有页面跳转均为相对路径，适合静态部署。
- 联系方式和版权信息已在每页底部左对齐显示。

## 联系方式

如有问题或建议，请联系：1709691060@qq.com

---

ZHANG Yichao Introduction Site © 2025