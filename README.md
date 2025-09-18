<div align="center">

# 🌉 SwiftBridge Exchange Platform

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-3.x-4FC08D?style=for-the-badge&logo=vue.js" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript" />
  <img src="https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-14.x-336791?style=for-the-badge&logo=postgresql" />
</p>

<h3>🚀 专业的 USDT 兑换平台解决方案</h3>
<p>快捷 · 安全 · 高效 · 匿名</p>

<p align="center">
  <a href="https://suqiaou.com"><strong>🌐 运营中产品</strong></a> •
  <a href="#核心功能"><strong>✨ 核心功能</strong></a> •
  <a href="#技术特点"><strong>🛠 技术特点</strong></a> •
  <a href="#快速部署"><strong>📦 快速部署</strong></a> •
  <a href="#商业授权"><strong>💼 商业授权</strong></a>
</p>

<br/>

<img src="https://raw.githubusercontent.com/yourusername/exchangecurrency-opensource/main/docs/images/preview.gif" alt="SwiftBridge Preview" width="80%" style="border-radius: 10px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);" />

</div>

---

## 🎯 项目简介

SwiftBridge 是一个专业的数字货币兑换平台解决方案，专注于 USDT 与法币的快速兑换。采用先进的匿名秘钥系统，无需用户注册即可完成交易，保护用户隐私的同时提供专业的金融服务体验。

### 🏆 为什么选择 SwiftBridge？

- **🔐 隐私保护** - 匿名秘钥系统，无需注册
- **⚡ 极速交易** - 3步完成兑换，简单高效
- **💰 灵活费率** - 智能分层费率，大额优惠
- **📱 全端适配** - 完美支持PC/平板/手机
- **🤖 自动化管理** - Telegram Bot 实时通知
- **🎨 专业UI** - 金融级界面设计

---

## ✨ 核心功能

### 💱 交易系统
- **实时汇率引擎** - 支持多币种实时汇率
- **智能费率计算** - 分层费率，自动计算最优价格
- **快速下单流程** - 3步完成：计算→信息→支付
- **订单状态追踪** - 实时查看订单处理进度

### 🔑 秘钥系统
- **匿名交易** - 无需注册账号
- **秘钥生成** - 自动生成唯一交易秘钥
- **订单查询** - 凭秘钥查询历史订单
- **安全加密** - SHA-256 哈希存储

### 👨‍💼 管理后台
- **订单管理** - 完整订单生命周期管理
- **汇率设置** - 实时调整各币种汇率
- **数据统计** - 交易量、收益等数据分析
- **用户管理** - 管理员权限控制

### 🤖 自动化通知
- **Telegram Bot** - 新订单实时推送
- **快捷操作** - 一键确认/拒绝订单
- **图片支持** - 自动发送收款二维码
- **群组管理** - 支持多管理员协作

---

## 🛠 技术特点

### 🎨 前端技术栈
```javascript
{
  "框架": "Vue.js 3.4 + Composition API",
  "语言": "TypeScript 5.x",
  "样式": "Tailwind CSS 3.x",
  "构建": "Vite 5.x",
  "状态管理": "Pinia 2.x",
  "路由": "Vue Router 4.x",
  "HTTP客户端": "Axios",
  "UI组件": "自研组件库"
}
```

### ⚙️ 后端技术栈
```javascript
{
  "运行时": "Node.js 20 LTS",
  "框架": "Express.js + TypeScript",
  "数据库": "PostgreSQL 14+",
  "ORM": "Prisma 5.x",
  "验证": "Zod",
  "认证": "JWT",
  "通知": "Telegram Bot API",
  "加密": "bcrypt + crypto"
}
```

### 🏗 架构特点
- **前后端分离** - API驱动的现代架构
- **模块化设计** - 高内聚低耦合
- **类型安全** - 全栈 TypeScript
- **安全防护** - XSS/CSRF/SQL注入防护
- **性能优化** - 缓存策略 + 懒加载
- **容器化部署** - Docker + Docker Compose

---

## 📦 快速部署

### 🐳 Docker 一键部署（推荐）

```bash
# 1. 克隆项目
git clone https://github.com/yourusername/exchangecurrency-opensource.git
cd exchangecurrency-opensource

# 2. 配置环境变量
cp .env.example .env
vim .env  # 编辑配置

# 3. 启动服务
docker-compose up -d

# 访问地址
# 用户前端: http://localhost:3001
# 管理后台: http://localhost:3002
# API服务: http://localhost:3000
```


### 🔧 手动部署

<details>
<summary>查看详细步骤</summary>

```bash
# 后端部署
cd backend
npm install
npm run build
npm run start

# 用户前端部署
cd user-frontend
npm install
npm run build
# 将 dist 目录部署到 CDN 或静态服务器

# 管理后台部署
cd admin-frontend
npm install
npm run build
# 将 dist 目录部署到 CDN 或静态服务器
```

</details>

---


## 💼 商业授权

### 开源协议
本项目采用 **MIT License** 开源协议，您可以：
- ✅ 免费用于个人或商业项目
- ✅ 自由修改和分发
- ✅ 私有化部署

### 专业版服务
如需专业技术支持，我们提供：
- 🎯 **定制开发** - 根据需求定制功能
- 🚀 **部署服务** - 一站式部署上线
- 💬 **技术支持** - 7×24 小时技术支持
- 📚 **培训服务** - 系统使用培训


---


## 📄 开源协议

本项目基于 [MIT](LICENSE) 协议开源

---


## 📞 联系我们

- **官网**: [https://suqiaou.com)
- telegram客服: @swiftbridge1024
- Telegram频道: @suqiao1024 


---

<div align="center">
  <br />
  <p>
    <sub>⭐ 如果这个项目对你有帮助，请给一个 Star！</sub>
  </p>
  <p>
    <sub>Built with ❤️ by <a href="https://github.com/yourusername">SwiftBridge Team</a></sub>
  </p>
</div>
