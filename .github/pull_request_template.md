# Pull Request Checklist

## 🧠 For All Contributors

- [ ] My code follows the Angular Style Guide.
- [ ] I ran `eslint` and `prettier` locally and fixed all issues.
- [ ] I added or updated tests for any logic I introduced.
- [ ] All new public APIs are documented with JSDoc.
- [ ] I manually tested the UI and verified it behaves as expected.

---

## 🧑‍🎓 For Junior Developers

- [ ] I avoided using `any` unless strictly necessary.
- [ ] I followed naming conventions for files and selectors.
- [ ] My component inputs/outputs are typed and validated.

---

## 🧑‍💻 For Mid-Level Developers

- [ ] I followed SOLID principles in new code.
- [ ] I used `trackBy` in `*ngFor` where applicable.
- [ ] I applied the `OnPush` change detection strategy where appropriate.
- [ ] I ensured lazy loading for new modules if needed.
- [ ] I wrote integration tests for business logic changes.

---

## 👨‍🏫 For Senior Developers

- [ ] I reviewed architecture for consistency with clean/hexagonal patterns.
- [ ] I validated bundle size impact using source-map explorer.
- [ ] I used feature flags or toggle strategies for risky changes.
- [ ] I checked for security vulnerabilities (e.g., via `npm audit`).
- [ ] I reviewed dependency changes and verified upgrade safety.

---

## 🧪 Tests

- [ ] `ng test` passes with no failures.
- [ ] Code coverage is above threshold or justified.

---

## 📝 Description

<!-- Write a short summary of your changes and the motivation behind them. Link issues when possible -->

---

## 🔍 Related Issues

Closes #  
Fixes #  
