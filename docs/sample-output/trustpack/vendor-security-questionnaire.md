# Vendor Security Questionnaire Starter Pack

Company: TrustPack Demo
Product: TrustPack Action
Repository: QuantumNavigator42/trustpack-action-demo
Generated: 2026-05-24T00:39:45.924Z

## How To Use

Review these starter responses before sending them to a buyer. Keep only answers that match your actual operating practices and attach the generated evidence reports when useful.

## Starter Responses

| Topic | Buyer Question | Starter Response | Evidence |
| --- | --- | --- | --- |
| Repository scope | Which repository was reviewed for this response? | TrustPack reviewed QuantumNavigator42/trustpack-action-demo with default branch main. | repository-evidence.json |
| Source control | Is the default branch protected? | Needs review. Branch protection could not be collected for main. | GitHub branch protection API |
| Code review | Are code ownership expectations documented? | Yes. CODEOWNERS found at .github/CODEOWNERS. | .github/CODEOWNERS |
| Security reporting | Do you publish vulnerability reporting instructions? | Yes. SECURITY.md found at SECURITY.md. | SECURITY.md |
| Dependency management | Do you have automated dependency update evidence? | Yes. Dependabot configuration found at .github/dependabot.yml. | .github/dependabot.yml |
| Dependency inventory | Can you provide dependency inventory evidence? | Yes. TrustPack detected 1 dependency manifest or lockfile record(s) across 1 ecosystem(s). | dependency-inventory.md |
| CI/CD workflow risk | Were GitHub Actions workflow risks reviewed? | Needs review. TrustPack detected 1 workflow risk finding(s). | github-actions-risk-report.md |
| Repository license | What repository license evidence is available? | Repository metadata reports MIT License (MIT). | open-source-license-notices.md |
| Release history | Can you provide release or tag evidence? | Needs review. No release or tag records were collected. | repository-evidence.json |
| Access review | Can you provide repository access review evidence? | Needs review. TrustPack v1 does not collect repository collaborators, teams, or access review records. | Provide access review exports or screenshots separately. |

## Review Before Sending

- [warning] Action reference is not pinned to a commit SHA: .github/workflows/trustpack.yml job trustpack step 2 uses QuantumNavigator42/trustpack-action@v0.1.0 without a full commit SHA pin.
- [unknown] Default branch protection: Branch protection could not be collected for main.
- [unknown] Repository rulesets: No repository rulesets were returned by the GitHub API.
- [unknown] Go dependency files: Go dependency files were not detected.
- [unknown] Maven dependency files: Maven dependency files were not detected.
- [unknown] Python dependency files: Python dependency files were not detected.
- [unknown] Rust dependency files: Rust dependency files were not detected.
- [unknown] Repository releases detected: No release records were returned by the GitHub API.
- [unknown] Repository tags detected: No tag records were returned by the GitHub API.

## Limitations

TrustPack helps collect repository-level security evidence. It is not legal, audit, or compliance certification.
