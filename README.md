# GARCH Quant — Hermes Agent Skills 技能包合集（脱敏版）

GARCH Quant 项目所有 Hermes Agent Skills 的主仓库，涵盖波动率建模、量化投研、学术出版等完整工具链。

## 技能包一览

| 技能 | 仓库 | 简介 |
|------|------|------|
| **garch-quant** | `garch-quant` | 波动率建模：GARCH/DCC/MIDAS/MS-GARCH/Realized GARCH/EVT VaR |
| **garch-alphaear** | `garch-alphaear` | A/H/US 市场情报：实时行情、新闻聚合、情绪分析、信号追踪 |
| **garch-gex-skill** | `garch-gex-skill` | 期权 GEX 分析：SPX/SPY/QQQ 期权链爬取、Gamma 翻转位识别 |
| **garch-stack** | `garch-stack` | A股风险量化：GJR-GARCH(1,1)-t + t-Copula VaR/CVaR |
| **garch-vol-report** | `garch-quant-vol-report` | 波动率周报：IV 曲面套利 + 跨资产Carry策略，8张图表 |
| **garch-nature-*** | `garch-nature-*` | Nature 投稿全套：引用/图表/PPT/润色/审稿回复 |
| **skill-creator** | `garch-skill-creator` | Skill 制作工具：初始化/打包/校验 |

## 凭证管理

所有 API Key 均通过环境变量注入，仓库内无硬编码凭证：

```bash
export TUSHARE_TOKEN="your_tushare_token"       # A股数据
export TWELVEDATA_KEY="your_twelve_data_key"    # 全球行情
export ALPHA_VANTAGE_KEY="your_alpha_vantage_key" # 美股数据
export TELEGRAM_BOT_TOKEN="***"                  # Telegram推送
```

## 开源说明

本仓库为脱敏开源版本，所有脚本可 fork 直接使用。实盘前请自行评估策略风险。
