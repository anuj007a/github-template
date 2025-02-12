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

## 📌 Change Type
- [ ] 🚀 **New Feature**
- [ ] 🐛 **Bug Fix**
- [ ] 📝 **Documentation Update**
- [ ] 🎨 **UI/UX Enhancement**
- [ ] 🔥 **Hotfix**
- [ ] 🛡️ **Security Patch**
- [ ] 🏗️ **Refactoring**

---

## 📝 Description of Changes
<!-- Provide a clear and concise summary of the changes made. -->  

---

## ✅ Pre-Review Checklist
- [ ] **Task Groomed & JIRA Documentation Attached**

### 🔍 **Code Quality & Testing**
- [ ] Unit Tests cover all relevant scenarios
- [ ] **Sonar Reliability Score:** A
- [ ] **E2E Execution Report Attached in PR**

### 🚀 **Pre-Deployment Validation**
- [ ] Feature validated in a **pre-prod environment**
- [ ] Performance & regression test results reviewed

### 📚 **Documentation & Compliance**
- [ ] API contracts, technical documentation, and SOPs updated

### 🚀 **Release Readiness**
- [ ] Release notes updated for features, changes, or fixes
- [ ] User-facing documentation updated (if applicable)

---

## 📜 Additional Information
<!-- Include extra details, logs, or screenshots if needed. -->  
