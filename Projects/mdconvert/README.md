# mdconvert

## 项目概述
mdconvert是一个轻量级Python库，提供简单易用的Markdown文档转换功能，支持将Markdown文档转换为HTML、PDF、DOCX等多种格式。

## 项目结构

### 核心模块
- **技术栈**：Python + Markdown解析 + HTML/PDF/DOCX生成
- **核心功能**：Markdown到多种格式的转换、自定义CSS样式、批量处理
- **详细信息**：查看 [开发日志](2026/03/README.md)

## 核心功能
- Markdown到HTML转换
- Markdown到PDF转换
- Markdown到DOCX转换
- 自定义CSS样式支持
- 批量文件处理
- 元数据提取

## 开发历程
- **2026年3月26日**：项目初始化，实现核心转换功能
- **2026年3月29日**：项目重命名为mdconvert，优化API设计

## 项目链接
- **GitHub**: https://github.com/Zheng-Enci/mdconvert
- **Gitee**: https://gitee.com/zheng-enci050704/mdconvert
- **GitCode**: https://gitcode.com/ZhengEnCi/mdconvert
- **PyPI**: https://pypi.org/project/mdconvert/

## 安装方式
```bash
pip install mdconvert
```

## 基本使用
```python
from mdconvert import MDConverter

# 创建转换器实例
converter = MDConverter(css_file="custom.css")

# 执行转换
converter.to_html(input_file, output_file, wrap_html=True)
```