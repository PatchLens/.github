# PatchLens

**Next-Level Go Dependency Update Validation**

PatchLens automates the discovery and risk assessment of behavior changes introduced by Go dependency updates. By combining static call-graph analysis, precise field-level and execution behavior inspections, PatchLens instantly identifies hidden regressions and subtle behavior shifts. Reducing manual testing, speeding up debugging, and helping you safely integrate updates.

---

## Core Benefits

* **Automatic Risk Detection**: Identify direct and indirect dependency impacts instantly.
* **Rapid Debugging**: Pinpoint exact locations and nature of code behavior changes.
* **Reduced Manual Testing**: Mutation testing and comprehensive execution monitoring significantly reduce manual efforts.
* **Improved Security**: Proactively manage dependency vulnerabilities.
* **Seamless CI Integration**: Easily integrates with Dependabot, Renovate, and manual workflows.

---

## Technical Approach

PatchLens leverages advanced static analysis and field-level inspection techniques. For a detailed explanation of our technical methodology, visit our [methodology page](https://patchlens.com/methodology).

---

## Get Started

### Open Source CLI

PatchLens is now available as an open-source tool. Download and run it directly from our [go-update-lens](https://github.com/patchlens/go-update-lens) repository.

### GitHub Action Integration

For automated CI/CD integration, use our [go-dep-impact-action](https://github.com/patchlens/go-dep-impact-action) which downloads and runs the PatchLens binary directly in your GitHub Actions workflow.

---

## Learn More

Visit [patchlens.com](https://patchlens.com/) to learn more about [our approach](https://patchlens.com/methodology) and how PatchLens can help you manage Go dependencies with confidence.

For questions or support, please [contact our team](https://patchlens.com/#contact).
