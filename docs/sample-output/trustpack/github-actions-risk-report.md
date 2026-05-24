# GitHub Actions Risk Report

Company: TrustPack Demo
Product: TrustPack Action
Repository: QuantumNavigator42/trustpack-action-demo
Generated: 2026-05-24T00:39:45.924Z

## Workflow Files

| Workflow | Triggers | Jobs |
| --- | --- | --- |
| .github/workflows/trustpack.yml | workflow_dispatch | trustpack |

## Risk Findings

- [warning] Action reference is not pinned to a commit SHA (medium): .github/workflows/trustpack.yml job trustpack step 2 uses QuantumNavigator42/trustpack-action@v0.1.0 without a full commit SHA pin.

## Limitations

TrustPack helps collect repository-level security evidence. It is not legal, audit, or compliance certification.
