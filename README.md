# 🔍 包装原创性检测工具

**Packaging Originality Check Tool** — 免费在线工具，帮助设计师/品牌方验证包装设计的原创性，零成本完成知识产权预排查。

🌐 **在线使用：** https://nyctocereusnicola.github.io/packaging-check/

---

## 功能模块

### 📷 以图搜图
上传包装图片 → 自动上传至免费图床获取公网URL → 一键跳转各大搜索平台：

| 平台 | 特点 |
|------|------|
| Google Lens | 全球最强图像识别，商品+电商精准匹配 |
| TinEye | 专业图片溯源，追踪图片原始来源 |
| Yandex 图片 | 相似图识别能力强，覆盖东欧+全球 |
| 百度识图 | 国内电商+全网，适合国内市场排查 |
| Bing 视觉搜索 | 微软图搜，覆盖欧美市场 |

### 🔤 关键词检索
输入产品名/品牌名/品类关键词，自动构造检索URL，一键跳转：

**专利检索：**
- [Google Patents](https://patents.google.com/) — 全球专利全文检索
- [国知局专利检索系统](https://pss-system.cponline.cnipa.gov.cn/) — 中国外观设计+发明专利
- [WIPO 外观设计数据库](https://www.wipo.int/designdb/) — 海牙体系国际外观设计
- [EU DesignView](https://www.tmdn.org/tmdsview-web/) — 欧盟外观设计
- [USPTO 外观专利](https://www.uspto.gov/patents/search) — 美国外观设计专利

**商标查询：**
- [国知局商标查询](https://sbj.cnipa.gov.cn/sbj/sbcx/) — 中国商标官方检索
- [TMview](https://www.tmdn.org/tmview/) — 全球商标数据库
- [USPTO 商标检索](https://tmsearch.uspto.gov/) — 美国商标

**品牌与企业：**
- [企查查](https://www.qcc.com/) / [天眼查](https://www.tianyancha.com/) — 企业信息+知识产权

### ✅ 自查清单
10项专业检测项（涵盖专利/商标/版权/全网比对/证据留存），支持：
- 勾选进度追踪（localStorage 持久化保存状态）
- 导出 TXT 格式检测报告

### 📝 创作证据留存
建立时间戳证据链的实用指引：
- ⚡ 区块链存证（阿里云/蚂蚁链，几元/次）
- 📜 著作权登记（中国版权保护中心，300-500元）
- 🏛️ 公证（适合高价值设计）
- 🗂️ 版本管理（Git commit 时间戳）

---

## 技术特点

- **零后端**：纯静态 HTML/CSS/JS，直接托管于 GitHub Pages
- **零费用**：所有跳转平台均为免费/公开平台
- **零数据收集**：不收集任何用户数据，图片仅上传到 catbox.moe 图床用于获取URL
- **国际化支持**：覆盖中国、欧盟、美国、国际专利/商标平台

---

## 本地使用

```bash
git clone https://github.com/nyctocereusnicola/packaging-check.git
cd packaging-check
# 直接用浏览器打开 index.html 即可
open index.html
```

---

## 适用场景

- 包装设计师：交稿前知识产权预排查
- 品牌方/甲方：验收设计稿原创性
- 出口贸易商：出口前外观专利冲突检查
- IP 顾问：快速初步排查工具

---

## 声明

本工具仅提供检索平台跳转，不提供法律意见。专业知识产权事务请咨询专业律师或知识产权代理机构。

---

Made with ❤️ | [在线访问](https://nyctocereusnicola.github.io/packaging-check/)
