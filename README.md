# 常规机电安装安装费价格库（网页版）

《常规机电安装安装费价格库_全国分项+地区系数_20261116.xlsx》的静态可视化版。

## 文件
- `index.html` —— 单页应用（首屏数据已内嵌，gzip 后约 20 KB）
- `region.json` —— 6507 行分地区明细（27省 × 241 分项），点开「分地区明细」标签页时按需加载

## 访问地址
- **网页入口（GitHub Pages，主地址）**：`https://1932yishui.github.io/mep-install-fee-db/`
  jsDelivr / statically / raw.githubusercontent 等纯文件 CDN 出于安全，一律把 `.html`
  按 `text/plain` 返回，浏览器只会显示源码、不渲染界面。**网页入口必须走 GitHub Pages。**
- **jsDelivr 节点（仅限非 HTML 资源，如 region.json）**：
```
https://cdn.jsdelivr.net/gh/1932yishui/mep-install-fee-db@v1.0.2/region.json
```
备用节点：
```
https://fastly.jsdelivr.net/gh/1932yishui/mep-install-fee-db@v1.0.2/region.json
https://gcore.jsdelivr.net/gh/1932yishui/mep-install-fee-db@v1.0.2/region.json
```

## 口径
安装费 = 人工 + 辅材 + 机械，**不含主材**。数据全部来自网络市场价与官方造价信息，
可追溯至工作簿「05_数据来源」表。
