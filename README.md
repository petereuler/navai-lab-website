# NavAI Lab 官方网站

这是NavAI Lab的官方网站，展示实验室的研究方向、团队成员和研究成果。

## 文件结构

```
M-Develop/
├── NavAI.html          # 主页面文件
├── images/             # 图片文件夹
│   ├── xm.jpg         # 夏鸣照片
│   ├── wjl.jpg        # 王家乐照片
│   ├── zzp.jpg        # 张展蓬照片
│   └── yzw.jpg        # 岳梓为照片
└── README.md          # 说明文件
```

## 部署方法

### 方法1：本地预览
1. 确保所有文件都在同一个文件夹中
2. 启动本地服务器：
   ```bash
   python3 -m http.server 8000
   ```
3. 在浏览器中访问：`http://localhost:8000/NavAI.html`

### 方法2：上传到服务器
1. 将整个文件夹上传到你的Web服务器
2. 确保`images`文件夹和`NavAI.html`在同一目录下
3. 通过域名访问网站

### 方法3：GitHub Pages
1. 将代码推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择主分支作为源
4. 访问生成的GitHub Pages链接

## 特性

- ✅ 响应式设计，支持各种设备
- ✅ 现代化UI设计，使用Tailwind CSS
- ✅ 团队成员滚动展示
- ✅ 平滑滚动和动画效果
- ✅ 中文界面，符合国内用户习惯

## 技术栈

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (原生)
- 响应式设计

## 注意事项

- 确保图片文件路径正确
- 如果部署到子目录，需要相应调整图片路径
- 建议使用现代浏览器以获得最佳体验
