<div align="center">

# NLP-DDL

自然语言处理会议、shared task 与评测挑战截止日追踪。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-10B981?style=for-the-badge)](https://just-agent.github.io/nlp-ddl/)
[![Just-DDL](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Demo-completed-059669?style=for-the-badge)](https://just-agent.github.io/nlp-ddl/)

[专题页面](https://just-agent.github.io/nlp-ddl/) · [Just-DDL Hub](https://just-agent.github.io/just-ddl/#/topic/nlp-ddl) · [GitHub 仓库](https://github.com/Just-Agent/nlp-ddl)

</div>

## Demo 已完善

这个仓库不再只是空 Pages 骨架。当前已经包含完整 demo DDL 列表、搜索筛选、状态统计、来源说明和统一 Just-DDL Network 导航。数据风格参考 AllConfs 的会议列表结构，以及 SinoConf 的国内会议/预告/回顾入口。

## Demo DDL Seed

| DDL | 阶段 | 截止日 | 地点 | 来源类型 |
| --- | --- | --- | --- | --- |
| ACL 2027 ARR Commitment | ARR commit | 2026-10-15 | Online | AllConfs-style seed |
| EMNLP 2026 Full Paper | Paper | 2026-06-16 | Online | Demo seed |
| NAACL 2027 Paper Submission | Paper | 2026-12-18 | Online | Demo seed |
| COLING 2027 Long Paper | Long paper | 2026-09-18 | Online | Demo seed |
| CoNLL Shared Task 2027 | System submit | 2027-01-20 | Online | Shared-task demo |
| SemEval 2027 System Submission | System | 2026-12-05 | Online | Shared-task demo |
| WMT 2027 Translation Task | Result upload | 2027-02-12 | Online | Benchmark demo |
| Chinese NLPCC 2026 Demo Track | Closed | 2026-05-01 | China | SinoConf-style seed |

## 后续生产化

| 模块 | 当前 | 下一步 |
| --- | --- | --- |
| 页面 | 完整 demo 页面已上线 | 替换为真实数据源输出 |
| 数据 | seed 数据在 index.html 内置 | 拆出 JSON/YAML schema |
| Actions | Pages 自动部署 | 增加 crawler、validator、link-check |
| Hub 联动 | 已接入 Just-DDL Hub | 加入更新时间和数据健康状态 |
| 小程序 | 结构已预留 | 复用同一 schema 输出小程序专题页 |

## References

- AllConfs: https://www.allconfs.org/
- SinoConf: https://sinoconf.napstic.cn/index

## License

当前仓库处于产品孵化阶段。正式开源协议会在发布稳定版本前补齐。