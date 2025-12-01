# 舞台灯光模拟器

## 字体配置说明

本项目已配置本地中文字体支持，确保在pakeplus打包后正常工作。

### 字体优先级

系统会按以下优先级使用字体：

1. **Microsoft YaHei** (微软雅黑) - Windows系统默认中文字体
2. **PingFang SC** (苹方) - macOS系统默认中文字体  
3. **Hiragino Sans GB** (冬青黑体) - macOS备选中文字体
4. **WenQuanYi Micro Hei** (文泉驿微米黑) - Linux系统常用中文字体
5. **SimHei** (黑体) - Windows系统备选字体
6. **SimSun** (宋体) - Windows系统备选字体
7. **NSimSun** (新宋体) - Windows系统备选字体
8. **FangSong** (仿宋) - Windows系统备选字体
9. **KaiTi** (楷体) - Windows系统备选字体
10. **STHeiti** (华文黑体) - macOS系统备选字体
11. **STKaiti** (华文楷体) - macOS系统备选字体
12. **STSong** (华文宋体) - macOS系统备选字体
13. **STFangsong** (华文仿宋) - macOS系统备选字体
14. **STZhongsong** (华文中宋) - macOS系统备选字体
15. **STLiti** (华文隶书) - macOS系统备选字体
16. **Arial** - 通用英文字体
17. **Helvetica** - 通用英文字体
18. **sans-serif** - 通用无衬线字体

### 应用范围

字体配置已应用到以下所有元素：

- 页面基础文本
- 控制面板按钮和文本
- dat.GUI界面元素
- Canvas绘制的ID标签
- 拍照功能中的文本标注
- 灯具组选择面板
- 框选提示信息

### 兼容性

- ✅ Windows系统 (使用微软雅黑)
- ✅ macOS系统 (使用苹方字体)
- ✅ Linux系统 (使用文泉驿微米黑)
- ✅ pakeplus打包后应用
- ✅ 离线环境运行

### 注意事项

1. 所有字体都使用系统内置字体，无需额外下载
2. 字体配置采用降级策略，确保在任何环境下都有合适的字体显示
3. 在pakeplus打包后，应用会优先使用系统字体，确保中文显示正常 