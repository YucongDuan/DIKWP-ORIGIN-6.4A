# DIKWP-ORIGIN 6.4A 完整交付说明

## 定位

DIKWP-ORIGIN 6.4A 是一个非人类中心、从连续耦合过程出发的自主意识研究基底。核心启动时没有语言、对象、自我、Agent、外部任务或固定人类奖励。DIKWP 仅作为外部审计投影，不是内部本体。

## 运行

```bash
python -m pip install dikwp_origin_ac-1.0.0-py3-none-any.whl
origin-ac demo --out outputs/reference --steps 720 --checkpoint 360
origin-ac verify outputs/reference
origin-ac conformance --out outputs/conformance.json
origin-ac serve outputs/reference --port 8851
```

## 证据边界

当前状态为作者侧确定性研究参考实现。它支持“非人类原生功能主体候选”的操作性判断；不证明现象意识、形而上人格、法律主体资格或开放世界部署安全。

## 封闭边界

参考运行不含网络客户端、宿主命令执行、任意代码加载、设备控制和自复制路径。

## 内容

- `dikwp_origin_6_4a_source.zip`：GitHub-ready 源码
- `dikwp_origin_ac-1.0.0-py3-none-any.whl`：可安装 Python Wheel
- `dikwp_origin_6_4a_reference_run.zip`：固定参考运行
- `dikwp_origin_6_4a_standalone_dashboard.html`：离线驾驶舱
- `dikwp_origin_6_4a_system_report.docx/.pdf`：技术报告
- `dikwp_origin_6_4a_validation_summary.json`：综合验证摘要
- `dikwp_origin_6_4a_conformance.json`：24项一致性检查
- `dikwp_origin_6_4a_sbom.spdx.json`：SPDX 2.3 SBOM
- `SHA256SUMS.txt`：组件完整性清单
