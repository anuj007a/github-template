# 🧰 Pull Request Template 🚀

Thank you for contributing! Please choose the appropriate template for your pull request from the options below: 👇

* **🐛 Bug Fix:** [bug_fix.md](.github/PULL_REQUEST_TEMPLATE/bug_fix.md)
* **📚 Documentation Update:** [documentation_update.md](.github/PULL_REQUEST_TEMPLATE/documentation_update.md)
* **✨ Feature:** [feature.md](.github/PULL_REQUEST_TEMPLATE/feature.md)
* **🔥 Hotfix:** [hotfix.md](.github/PULL_REQUEST_TEMPLATE/hotfix.md)
* **🛠️ Refactoring:** [refactoring.md](.github/PULL_REQUEST_TEMPLATE/refactoring.md)
* **🛡️ Security Patch:** [security-patch.md](.github/PULL_REQUEST_TEMPLATE/security-patch.md)
* **🎨 UI/UX Improvement:** [ui-ux-improvement.md](.github/PULL_REQUEST_TEMPLATE/ui-ux-improvement.md)

## 💡 Selecting the Right Template

To use a specific template, add the `template` query parameter to the URL when creating your pull request.  For example, to use the "Bug Fix" template:

1. Start creating your pull request as usual.
2. On the "Compare" page (where you select the branches), append `?template=bug_fix.md` to the URL.  It should look something like this:
`https://github.com/YOUR_USERNAME/YOUR_REPO/compare/YOUR_BASE_BRANCH...YOUR_COMPARE_BRANCH?template=bug_fix.md`
3. The "Bug Fix" template will then be loaded.
4. **Delete** these instructions before creating the pull request.

**Note:** If you don't specify a template using the URL parameter, this default template (`PULL_REQUEST_TEMPLATE.md`) will be used.

---

<!-- Pull Request Template -->

## 📌 Title
<!-- Provide a succinct and descriptive title for the PR -->
Example: **Improve caching mechanism for API calls**

## 📂 Type of Change
- [ ] 🚀 New Feature
- [ ] 🐛 Bug Fix
- [ ] 📝 Documentation Update
- [ ] 🎨 UI/UX Improvement
- [ ] 🔥 Hotfix
- [ ] 🛡️ Security Patch
- [ ] 🏗️ Refactoring

## 📖 Description
<!-- Describe the purpose of the changes, reasoning, and relevant context -->
Fixes #[Issue Number]

## 🛠️ How Has This Been Tested?
- [ ] Unit Tests
- [ ] Integration Tests
- [ ] Manual Testing
- [ ] Performance Tests

## ⚡ Impact
<!-- Discuss effects on performance, dependencies, or behavior changes -->

## 📎 Related Issues/Tickets
<!-- Link related issues, e.g., Fixes #123 -->

## 📜 Additional Information
<!-- Add any extra details, screenshots, or logs if needed -->

## ✅ Checklist
- [ ] Code follows the project's coding guidelines.
- [ ] Changes are well-documented.
- [ ] No new warnings or errors introduced.
- [ ] Relevant tests have been added and pass.

