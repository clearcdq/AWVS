# AWVS - 高级网站漏洞扫描器

![License](https://img.shields.io/badge/License-MIT-blue.svg) ![Language](https://img.shields.io/badge/Language-Multiple-brightgreen) ![Status](https://img.shields.io/badge/Status-Active-success)

> 🔍 AWVS（Acunetix Web Vulnerability Scanner）资源集合和使用指南

## 📋 项目概述

AWVS 是业界领先的网站漏洞扫描工具，本仓库收集了 AWVS 相关的配置文件、脚本和使用文档。

## ⚠️ 免责声明

本项目所涉及的技术、思路和工具仅供学习使用，任何人不得将其用于非法用途或未授权渗透测试，违者后果自行承担。

## 🎯 主要特性

- 🔐 **全面的漏洞检测** - 支持 OWASP Top 10 及以上漏洞
- 🚀 **高效扫描引擎** - 支持并发扫描
- 📊 **详细的报告** - 支持多种报告格式导出
- 🛠️ **灵活的配置** - 支持自定义扫描规则

## 📚 使用指南

### 基础使用

```bash
# 启动 AWVS
Awvs.exe

# 登录系统
# 默认用户名: admin
# 默认密码: admin
```

### 配置扫描

1. 登录 AWVS 管理界面
2. 添加目标 URL
3. 选择扫描配置
4. 启动扫描
5. 查看扫描报告

## 📂 文件结构

```
AWVS/
├── README.md              # 本文件
├── config/               # 配置文件
├── scripts/              # 自动化脚本
├── rules/                # 扫描规则
└── docs/                 # 使用文档
```

## 💡 最佳实践

### 扫描前准备

- 获得目标网站所有者的书面授权
- 在测试环境进行初步测试
- 准备充足的时间（根据网站规模）
- 备份重要数据

### 扫描配置建议

- **快速扫描** - 用于快速检查
- **完整扫描** - 用于全面审计
- **自定义扫描** - 根据需求定制

## 🔧 常见问题

### Q: 如何导出扫描报告？
A: 在扫描完成后，点击 "生成报告" 按钮，选择导出格式（PDF/HTML/XML）。

### Q: 如何添加自定义漏洞检测？
A: 在规则编辑器中创建新规则，或从社区获取现有规则。

## 📊 支持的漏洞类型

| 漏洞类型 | 检测能力 | 严重级别 |
|--------|--------|--------|
| SQL 注入 | ✅ | 严重 |
| XSS | ✅ | 高 |
| CSRF | ✅ | 中 |
| 身份验证漏洞 | ✅ | 高 |
| 业务逻辑漏洞 | ✅ | 中 |

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

## 📞 联系方式

- **GitHub Issues** - 提交问题
- **Email** - clearcdq@gmail.com

## 📄 许可证

MIT License

---

**最后更新**: 2026年6月  
**维护者**: [@clearcdq](https://github.com/clearcdq)