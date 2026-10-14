<div align="center">

# proxy-rule-scripts

**自用 Loon 规则集。** 一个 App 一个插件，规则直接写在文件里 —— 无构建、无外部依赖、无中间层，所见即所得。

[![Stars](https://img.shields.io/github/stars/yangxiaopeipei/proxy-rule-scripts?style=for-the-badge&logo=github&labelColor=24292f&color=ffd700&label=Stars)](https://github.com/yangxiaopeipei/proxy-rule-scripts/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/yangxiaopeipei/proxy-rule-scripts?style=for-the-badge&logo=git&labelColor=24292f&color=60c5ba&label=更新)](https://github.com/yangxiaopeipei/proxy-rule-scripts/commits/main)
[![License](https://img.shields.io/github/license/yangxiaopeipei/proxy-rule-scripts?style=for-the-badge&labelColor=24292f&color=1E90FF&label=许可)](https://github.com/yangxiaopeipei/proxy-rule-scripts/blob/main/LICENSE)

</div>

---

## 📦 订阅

| App | 处理内容 | 导入 |
| :-: | :-- | :-: |
| <img src="https://raw.githubusercontent.com/luestr/IconResource/main/App_icon/120px/HUPU.png" width="22" alt="虎扑"><br>**虎扑** | 开屏 / 插屏广告<br>首页与列表推广位<br>我的页推广模块、论坛推广入口 | [一键导入](https://www.nsloon.com/openloon/import?plugin=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fyangxiaopeipei%2Fproxy-rule-scripts%40main%2FLoon%2FPRS_HUPU.plugin) |

<details>
<summary>订阅地址与备用导入方式</summary>

在 Loon → 插件 → 右上角 `+` → URL 里粘贴：

```plaintext
https://cdn.jsdelivr.net/gh/yangxiaopeipei/proxy-rule-scripts@main/Loon/PRS_HUPU.plugin
```

也可以写进主配置的 `[Plugin]` 段：

```plaintext
https://cdn.jsdelivr.net/gh/yangxiaopeipei/proxy-rule-scripts@main/Loon/PRS_HUPU.plugin, enabled=true
```

Safari 打不开上面的「一键导入」时，直接用这个 Scheme：

```plaintext
loon://import?plugin=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fyangxiaopeipei%2Fproxy-rule-scripts%40main%2FLoon%2FPRS_HUPU.plugin
```

</details>

> 直连 `raw.githubusercontent.com` 通常不通，所以走 jsDelivr。
> jsDelivr 有缓存，更新后可能要等几分钟才生效，急用就在链接后面加 `?t=<时间戳>`。

---

## 免责

自用整理，规则多来自公开互联网与他人开源项目，仅供学习与个人使用。不保证时效性与可用性，App 升级后部分规则可能失效。

本仓库以 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 许可发布 —— **禁止商用**。
