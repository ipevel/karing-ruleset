# Clash Rulesets

Clash Meta / Mihomo 分流规则集，兼容 Xboard 等面板。

## 目录结构

```
clashmeta/
├── providers/                        # 规则 provider 文件（23个分类）
├── clash-full.clash.yaml            # 完整规则集
├── clash-selected.clash.yaml        # 精选规则集
└── clash-xboard-subscription.yaml   # Xboard 订阅模板
```

## 使用方式

### Xboard 模板

在 Xboard 的 Clash Meta 订阅模板系统中导入 `clash-xboard-subscription.yaml`。

### 规则 Provider（CDN）

通过 jsDelivr CDN 托管的 provider 文件：

```
https://fastly.jsdelivr.net/gh/ipevel/clash-rulesets@main/clashmeta/providers/Google.yaml
```

### 独立配置文件

将 `clash-full.clash.yaml` 或 `clash-selected.clash.yaml` 作为独立的 Clash Meta 配置文件使用（在 `proxies:` 节点处填入你的代理节点）。
