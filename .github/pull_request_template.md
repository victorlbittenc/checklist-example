## Mandatory

- [ ] Naming convention
- [ ] No duplication of code
- [ ] No magic entities
- [ ] Constants come from libraries or model files
- [ ] Clean translation files
- [ ] No console.log, debugger or comments
- [ ] **readonly** on immutable properties
- [ ] No use of **any**
- [ ] @for calls have a [track](https://angular.dev/api/core/@for#track-and-objects-identity) function
- [ ] Methods follow SRP

---

## Desirable

- [ ] Layer separation(presentation, domain and data)
- [ ] Pure functions whenever possible
- [ ] Low cyclomatic complexity
- [ ] Employ TypeScript generics to broaden the flexibility of methods
- [ ] Efficient use of iterators
- [ ] Use the async pipe whenever possible and, when not, manually unsubscribe on ngOnDestroy
- [ ] Library methods are described with [JSDoc](https://jsdoc.app/about-getting-started)

---

## Tests

- [ ] `npm run test` passes with no failures.
- [ ] Coverage of new code is above 80%