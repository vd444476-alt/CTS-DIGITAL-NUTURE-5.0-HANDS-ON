# Angular Hands-On Exercise Book — Digital Nurture 5.0

**Track:** .NET Full Stack Engineer | **Angular Version:** v20.0
**Program:** Cognizant Digital Nurture 5.0 Deep Skilling Program

## Overview

This exercise book contains 10 progressive hands-on exercises covering Angular fundamentals through advanced state management and testing. All exercises build a single, continuously evolving application — the **Student Course Portal** — rather than separate standalone projects per exercise.

The Student Course Portal allows students to view their profile, browse and enroll in courses, check grades, and receive notifications, while administrators can manage course listings.

## Software & Tools Required

- Node.js (LTS 20+) + npm
- Angular CLI v20 (`npm install -g @angular/cli`)
- VS Code + Angular Language Service extension
- Chrome + Angular DevTools extension
- JSON Server (mock REST API) (`npm install -g json-server`)

## Difficulty Progression

| Level | Hands-On | Focus |
|-------|----------|-------|
| Beginner | 1, 2, 3 | Project setup, components, bindings, directives, pipes |
| Intermediate | 4, 5, 6, 7 | Forms, validation, services, DI, routing, guards |
| Advanced | 8, 9, 10 | HTTP client, interceptors, NgRx, RxJS, unit testing |

## Hands-On Breakdown

1. **Environment Setup, Project Structure & First Component** — Scaffold the project with Angular CLI, understand the generated file structure, and create the Header/Home/CourseList/StudentProfile components.
2. **Data Binding, Lifecycle Hooks & Component Communication** — Practice interpolation, property/event/two-way binding, `ngOnInit`/`ngOnChanges`/`ngOnDestroy`, and parent-child communication via `@Input`/`@Output`.
3. **Directives & Pipes** — Apply structural directives (`*ngIf`, `*ngFor`, `*ngSwitch`), attribute directives (`ngClass`, `ngStyle`), and build a custom directive and custom pipe.
4. **Template-Driven Forms & Validation** — Build the Enrollment Request form using `ngModel`, built-in validators, and contextual error messages.
5. **Reactive Forms** — Rebuild the enrollment form with `FormBuilder`/`FormGroup`, add custom sync/async validators, and use `FormArray` for dynamic controls.
6. **Services & Dependency Injection** — Create `CourseService` and `EnrollmentService`, explore `providedIn: 'root'`, singleton behavior, and hierarchical DI.
7. **Routing — Guards, Lazy Loading & Route Data** — Configure routes, route/query parameters, nested routes, lazy-loaded feature modules, `CanActivate` and `CanDeactivate` guards.
8. **HTTP Client — API Integration & Interceptors** — Replace hardcoded data with `HttpClient` calls against JSON Server, apply RxJS operators (`map`, `catchError`, `tap`, `retry`, `switchMap`), and build auth/error/loading interceptors.
9. **State Management — NgRx** — Set up the NgRx store with actions, reducers, selectors, and effects to manage course and enrollment state.
10. **Unit Testing — Jasmine, Karma & TestBed** — Write component and service tests, including `HttpClientTestingModule` and `MockStore` for NgRx-connected components.

## Submission Guidelines

- Solutions organized in a folder named `Angular_HandsOn/<YourName>/`
- Complete Angular project folder submitted (`node_modules` excluded via `.gitignore`)
- Single evolving project across all 10 hands-on exercises
- Pushed to GitHub repository, URL shared with POC

---
*Digital Nurture 5.0 — For Participants Only*
