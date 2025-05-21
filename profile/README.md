# PatchLens

**Next-Level Go Dependency Update Validation**

PatchLens is an automated analysis tool that helps Go developers safely and efficiently manage dependency updates. By deeply analyzing code and test suites, PatchLens identifies hidden risks and behavior changes introduced by both direct and indirect module upgrades.

---

## How It Works

PatchLens performs a multi-phase analysis to assess the impact of dependency changes:

1. **Analyze**  
   - Detects changes in updated modules, including transitive dependencies.  
   - Uses static analysis to trace call paths from your codebase to the changed dependency functions.  
   - Analyzes existing unit tests to establish a baseline for validation.

2. **Expand**  
   - Identifies key points in the code to monitor field values, capturing behavior changes throughout the project.  
   - Utilizes AI to expand unit tests, enhancing coverage of change-affected areas.  
   - Employs field-level inspection to detect behavior changes without relying solely on assertions.

3. **Validate**  
   - Executes tests multiple times to distinguish stable fields from unstable ones, focusing on meaningful changes.  
   - Assesses risk by analyzing field state changes at points where your project interacts with updated module functions.  
   - Measures confidence by introducing intentional mutations in the updated module and verifying that the test suite detects these injected defects.

---

## Integrate with Your CI/CD Pipeline

PatchLens is designed to integrate seamlessly into your continuous integration workflows. It complements tools like Dependabot by providing in-depth analysis and validation reports specific to each dependency update.

---

## Free for Open Source Projects

We offer PatchLens for free to open source projects on GitHub that are public and use compatible licenses (Apache 2.0, MIT, BSD, or MPL). For integration details, refer to our [go-dep-impact-action](https://github.com/patchlens/go-dep-impact-action) repository.

---

## Learn More

Visit [patchlens.com](https://patchlens.com/) to learn more about our approach and how PatchLens can help you manage Go dependencies with confidence.

For questions or support, please [contact our team](https://patchlens.com/#contact).
