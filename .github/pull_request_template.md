# Pull Request Guidelines

## Relevant links

## Description

## Mandatory

- [ ] Good naming convention(Names are written in english, have no typos and state clearly their purpose)
- [ ] No duplication of code
- [ ] No magic entities
- [ ] Clean translation files: no links, no HTML, etc
- [ ] No console.log or debugging tools in code
- [ ] Code has no comments
- [ ] Use readonly for immutable properties
- [ ] Employ TypeScript generics to broaden the flexibility of methods
- [ ] Functions, classes and interfaces are fully typed(i.e., don't use any)
- [ ] Single Responsibility Principle

---

## Desirable

- [ ] Angular entities(services, components, pipes etc) follow single responsibility
- [ ] Clear separation between presentation, domain and data layers
- [ ] Pure functions whenever possible
- [ ] Aim for low cyclomatic complexity
- [ ] Efficient use of iterators
- [ ] Use the async pipe whenever possible and, when not, manually unsubscribe on ngOnDestroy
- [ ] Use JSDoc(https://jsdoc.app/about-getting-started) when inserting new methods into services lib
- [ ] Use track with @for and trackBy with *ngFor to minimize re-rendering(https://angular.dev/api/core/@for#track-and-objects-identity)

---

## Tests

- [ ] `npm run test` passes with no failures.
- [ ] Coverage of new code is above 80%