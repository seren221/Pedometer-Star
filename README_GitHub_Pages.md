# 在GitHub Pages部署计步星隐私政策

## 操作步骤

### 1. 创建GitHub仓库
1. 登录 [GitHub](https://github.com)
2. 点击右上角的 "+" 号，选择 "New repository"
3. 仓库名称填写：`stepstar-privacy`（或其他你喜欢的名称）
4. 设置为 **Public**（公开仓库）
5. 勾选 "Add a README file"
6. 点击 "Create repository"

### 2. 上传隐私政策文件
1. 在新创建的仓库页面，点击 "Add file" → "Upload files"
2. 将项目根目录下的 `privacy.html` 文件拖拽到上传区域
3. 在页面底部填写提交信息：
   - Commit title: `Add privacy policy`
   - Description: `Initial privacy policy for StepStar app`
4. 点击 "Commit changes"

### 3. 启用GitHub Pages
1. 在仓库页面，点击 "Settings" 选项卡
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分：
   - 选择 "Deploy from a branch"
   - Branch 选择 "main"
   - Folder 选择 "/ (root)"
4. 点击 "Save"
5. 等待几分钟，页面会显示绿色的成功消息和访问链接

### 4. 获取隐私政策链接
部署成功后，你的隐私政策链接将是：
```
https://你的GitHub用户名.github.io/stepstar-privacy/privacy.html
```

例如，如果你的GitHub用户名是 `zhangsan`，链接就是：
```
https://zhangsan.github.io/stepstar-privacy/privacy.html
```

### 5. 在小米开发者后台填写
将上述链接复制到小米快应用开发者后台的"隐私协议"字段中。

## 注意事项

1. **确保仓库是公开的**：私有仓库无法使用GitHub Pages
2. **等待部署完成**：首次部署可能需要5-10分钟
3. **测试链接**：在提交审核前，请先访问链接确保页面正常显示
4. **保持内容一致**：确保线上隐私政策与应用内容一致

## 如果需要修改隐私政策

1. 在GitHub仓库中直接编辑 `privacy.html` 文件
2. 提交更改后，GitHub Pages会自动更新
3. 通常在几分钟内生效

## 备用方案

如果GitHub访问有问题，也可以使用：
- **Gitee Pages**：国内访问更快
- **Vercel**：部署简单，速度快
- **Netlify**：功能强大，免费额度充足

选择任一平台，上传 `privacy.html` 文件即可获得HTTPS链接。