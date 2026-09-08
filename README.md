# DIKWP-ORIGIN 6.4A

**A continuous-coupling substrate for autonomous-consciousness research.**

[Chinese reference](README.zh-CN.md) · [Download the complete delivery](dikwp_origin_6_4a_full_delivery.zip) · [Research hub](https://github.com/YucongDuan/YucongDuan)

ORIGIN 6.4A explores a research substrate that starts from continuous coupled processes. Its core initialization does not prespecify language, objects, a self, an agent, an external task or a fixed human reward. DIKWP serves as an external audit projection rather than the core's internal ontology.

## Extract the release first

The runtime and reports are distributed inside `dikwp_origin_6_4a_full_delivery.zip`. Download and extract that archive, then locate the directory containing `dikwp_origin_ac-1.0.0-py3-none-any.whl`. Run the following commands from that directory:

```bash
python -m pip install dikwp_origin_ac-1.0.0-py3-none-any.whl
origin-ac demo --out outputs/reference --steps 720 --checkpoint 360
origin-ac verify outputs/reference
origin-ac conformance --out outputs/conformance.json
origin-ac serve outputs/reference --port 8851
```

## Included artifacts

| Artifact inside the delivery | Purpose |
|---|---|
| `dikwp_origin_6_4a_source.zip` | Source package |
| `dikwp_origin_ac-1.0.0-py3-none-any.whl` | Installable Python wheel |
| `dikwp_origin_6_4a_reference_run.zip` | Recorded reference run |
| `dikwp_origin_6_4a_standalone_dashboard.html` | Offline dashboard |
| `dikwp_origin_6_4a_system_report.docx` / `.pdf` | Technical report |
| `dikwp_origin_6_4a_validation_summary.json` | Original validation summary |
| `dikwp_origin_6_4a_conformance.json` | Original record of 24 conformance checks |
| `dikwp_origin_6_4a_sbom.spdx.json` | SPDX 2.3 software bill of materials |
| `SHA256SUMS.txt` | Component integrity manifest |

## Evidence scope

The original release describes an author-side deterministic research reference implementation. It supports operational investigation of a non-human-native functional subject candidate. It does not establish phenomenal consciousness, metaphysical personhood, legal subject status or safe open-world deployment.

The reference execution excludes network clients, host-command execution, arbitrary code loading, device control and self-replication paths. The documented server command is part of inspecting generated results.

## Language and verification

This README is the English entry point; the packaged artifacts retain their original release languages. Original validation files describe their original build. No new runtime tests were executed for this translation.

See [LICENSE](LICENSE) before redistribution.
