# Angular Frontend Software Engineer

## 🎯 Nivel Junior

### Fundamentos Angular

#### TypeScript Basics (Prerequisito)
*Qué aprenderás:*
- Tipos básicos: `string`, `number`, `boolean`, `array`, `object`
- Interfaces básicas y type annotations
- Clases: constructor, propiedades, métodos
- Modules: `import`/`export`, default exports
- Generics básicos: `<T>`, constraints simples
- Enums y union types básicos

*Recursos:*
- **Gratuito:** TypeScript Handbook oficial
- **Udemy:** "Understanding TypeScript" por Maximilian Schwarzmüller
- **Angular:** TypeScript configuration guide
- **Práctica:** TypeScript Playground, migración gradual JS→TS

#### Angular Fundamentals

#### Arquitectura y Setup
*Qué aprenderás:*
- Angular CLI: `ng new`, `ng generate`, `ng serve`, `ng build`
- Estructura de proyecto: `src/app`, `assets`, `environments`
- Angular DevKit: schematics básicos, workspace configuration
- Package.json y dependencies: `@angular/core`, `@angular/common`
- Compilation process: AOT vs JIT básico
- Browser support y polyfills

*Recursos:*
- **Gratuito:** Angular.io Getting Started
- **Udemy:** "Angular - The Complete Guide" por Maximilian Schwarzmüller
- **YouTube:** Angular University, Decoded Frontend
- **Práctica:** Angular CLI Workspaces guide

#### Components y Templates
*Qué aprenderás:*
- Component anatomy: `@Component` decorator, selector, template, styles
- Data binding: interpolación `{{}}`, property binding `[]`, event binding `()`
- Two-way binding: `[(ngModel)]`, FormsModule
- Template reference variables: `#templateVar`
- Component communication: `@Input()`, `@Output()`, `EventEmitter`
- Lifecycle hooks básicos: `ngOnInit`, `ngOnDestroy`
- Component styles: encapsulation, `:host`, `::ng-deep`

*Recursos:*
- **Angular.io:** Component guide, Template syntax
- **Udemy:** Component communication patterns
- **YouTube:** Joshua Morony component tutorials
- **Práctica:** Tour of Heroes tutorial completo

#### Directives
*Qué aprenderás:*
- Built-in directives: `*ngIf`, `*ngFor`, `[ngClass]`, `[ngStyle]`
- Structural vs Attribute directives
- Custom attribute directives: `@Directive`, `ElementRef`, `Renderer2`
- `@HostListener`, `@HostBinding` básicos
- Directive composition: applying multiple directives

*Recursos:*
- **Angular.io:** Directives guide
- **Medium:** Angular directives deep dive articles
- **GitHub:** Angular directive examples
- **Práctica:** Crear highlight directive, tooltip directive

#### Services y Dependency Injection
*Qué aprenderás:*
- `@Injectable()` decorator y metadata
- Service creation: `ng generate service`
- Dependency Injection básico: constructor injection
- Providers: `providedIn: 'root'`, module-level providers
- Service lifetime: singleton pattern en Angular
- HTTP básico: `HttpClient`, GET requests, observables básicos

*Recursos:*
- **Angular.io:** Services guide, Dependency Injection
- **RxJS:** Basic observables introduction
- **Udemy:** Angular services y HTTP
- **Práctica:** CRUD service con JSONPlaceholder API

### Routing Básico

#### Angular Router
*Qué aprenderás:*
- Router setup: `RouterModule.forRoot()`, `<router-outlet>`
- Route configuration: `path`, `component`, `redirectTo`
- Navigation: `routerLink`, `Router.navigate()`
- Route parameters: `ActivatedRoute`, `snapshot.paramMap`
- Query parameters y fragments básicos
- Route guards básicos: `CanActivate` introduction

*Recursos:*
- **Angular.io:** Routing guide
- **YouTube:** Angular routing tutorials
- **Udemy:** Angular router deep dive
- **Práctica:** Multi-page application con parámetros

### Forms Básicos

#### Template-driven Forms
*Qué aprenderás:*
- FormsModule import y setup
- `ngModel` y two-way binding
- Form validation: `required`, `minlength`, `maxlength`, `pattern`
- Template reference variables en forms: `#form="ngForm"`
- Validation states: `valid`, `invalid`, `touched`, `dirty`
- Error handling: `*ngIf` con validation errors

*Recursos:*
- **Angular.io:** Forms guide
- **Angular:** Validation examples
- **YouTube:** Angular forms tutorials
- **Práctica:** Contact form, registration form

### Testing Básico

#### Unit Testing Introduction
*Qué aprenderás:*
- Jasmine basics: `describe`, `it`, `expect`
- Karma test runner setup
- TestBed: `configureTestingModule`, component testing setup
- Component testing: `fixture.detectChanges()`, `DebugElement`
- Service testing: dependency injection en tests
- Async testing básico: `fakeAsync`, `tick`

*Recursos:*
- **Angular.io:** Testing guide
- **YouTube:** Angular testing tutorials
- **Udemy:** Angular testing course
- **Práctica:** Test driven development básico

---

## 💪 Nivel Proficient

### Angular Intermedio

#### Advanced Components

#### Component Architecture
*Qué aprenderás:*
- Smart vs Presentational components pattern
- Component composition: `ng-content`, content projection
- Dynamic component creation: `ComponentFactoryResolver`, `ViewContainerRef`
- Component inheritance: extending base classes
- All lifecycle hooks: `ngOnChanges`, `ngDoCheck`, `ngAfterContentInit`, etc.
- Change detection strategies: `OnPush`, `ChangeDetectorRef`
- ViewChild y ContentChild: `@ViewChild`, `@ContentChild`, `@ViewChildren`

*Recursos:*
- **Angular.io:** Lifecycle hooks, Dynamic components
- **Medium:** Angular architecture patterns
- **YouTube:** Angular University advanced patterns
- **Práctica:** Reusable modal, accordion, tab components

#### Advanced Directives
*Qué aprenderás:*
- Structural directive creation: `ng-template`, `TemplateRef`, `ViewContainerRef`
- Advanced `@HostListener`: keyboard events, window events
- Directive communication: `@Output` en directives
- Multi-element directives: working con element queries
- Performance considerations: OnPush directives

*Recursos:*
- **Angular.io:** Structural directives guide
- **Blog posts:** Custom structural directives
- **GitHub:** Angular directive libraries source
- **Práctica:** Custom *ngFor, conditional directives

### Forms Avanzados

#### Reactive Forms
*Qué aprenderás:*
- ReactiveFormsModule: `FormControl`, `FormGroup`, `FormArray`
- FormBuilder service: reducing boilerplate code
- Validators: built-in, custom validators, async validators
- Dynamic forms: programmatic form creation
- Form value changes: `valueChanges`, `statusChanges` observables
- Cross-field validation: group-level validators
- Nested forms: `FormGroup` dentro de `FormGroup`

*Recursos:*
- **Angular.io:** Reactive forms guide
- **Udemy:** Angular reactive forms mastery
- **YouTube:** Decoded Frontend forms
- **Práctica:** Dynamic survey builder, nested address forms

#### Custom Form Controls
*Qué aprenderás:*
- `ControlValueAccessor` interface implementation
- `writeValue`, `registerOnChange`, `registerOnTouched`
- Custom validation: `Validator` interface
- Form control integration: working con `FormControl`
- Accessibility: proper ARIA attributes

*Recursos:*
- **Angular.io:** Custom form controls
- **Medium:** ControlValueAccessor deep dive
- **Stack Overflow:** Common form control patterns
- **Práctica:** Custom date picker, rating component

### RxJS Intermedio

#### Observables y Operators
*Qué aprenderás:*
- Observable creation: `of`, `from`, `interval`, `fromEvent`
- Transformation operators: `map`, `switchMap`, `mergeMap`, `concatMap`
- Filtering: `filter`, `take`, `takeUntil`, `debounceTime`
- Combination: `combineLatest`, `merge`, `zip`, `startWith`
- Error handling: `catchError`, `retry`, `finalize`
- Subscription management: `unsubscribe`, `takeUntil` pattern

*Recursos:*
- **RxJS.dev:** Official documentation
- **YouTube:** RxJS tutorials por Angular University
- **Interactive:** RxJS marbles visualization
- **Udemy:** RxJS reactive programming
- **Práctica:** Search autocomplete, real-time data dashboards

### HTTP y State Management

#### Advanced HTTP
*Qué aprenderás:*
- HTTP interceptors: request/response modification
- Error handling: global error handling, retry strategies
- Caching strategies: HTTP cache headers, custom caching
- File upload/download: FormData, progress tracking
- Authentication: JWT tokens, refresh token patterns
- CORS handling y preflight requests

*Recursos:*
- **Angular.io:** HTTP guide, Interceptors
- **Medium:** Angular HTTP best practices
- **GitHub:** HTTP interceptor examples
- **Práctica:** REST API integration, file upload service

#### State Management Patterns
*Qué aprenderás:*
- Service-based state: shared services, BehaviorSubject
- State management principles: immutability, single source of truth
- Simple state stores: manual store implementation
- Communication patterns: parent-child, sibling communication
- Event bus pattern: service-based event system

*Recursos:*
- **Angular.io:** Service communication patterns
- **Medium:** Angular state management without NgRx
- **YouTube:** State management patterns
- **Práctica:** Shopping cart, user preferences store

### Routing Avanzado

#### Advanced Router Features
*Qué aprenderás:*
- Nested routing: child routes, outlet configuration
- Route guards: `CanActivate`, `CanDeactivate`, `CanLoad`
- Resolvers: `Resolve` interface, pre-loading data
- Lazy loading: feature modules, route-based splitting
- Route data y configuration: static data passing
- Custom route matching: `UrlMatcher` function

*Recursos:*
- **Angular.io:** Advanced routing guide
- **YouTube:** Angular router deep dive
- **Udemy:** Angular routing mastery
- **Práctica:** Admin dashboard con nested routes

### Testing Intermedio

#### Component Testing
*Qué aprenderás:*
- Advanced TestBed: custom providers, mock services
- Component integration testing: template y component interaction
- Forms testing: reactive forms, validation testing
- Router testing: navigation, route parameters
- HTTP testing: `HttpClientTestingModule`, mock requests
- Async testing: promises, observables, `fakeAsync`

*Recursos:*
- **Angular.io:** Testing components y services
- **YouTube:** Angular testing techniques
- **Books:** Angular testing best practices
- **Práctica:** Complete component test suites

---

## 🚀 Nivel Senior

### Architecture & Design Patterns

#### Angular Architecture Patterns
*Qué aprenderás:*
- Feature modules: lazy loading, shared modules
- Core/Shared module pattern: singleton services, common utilities
- Barrel exports: clean import statements
- Facade pattern: service layer abstraction
- Container/Presenter pattern: smart/dumb components
- Plugin architecture: dynamic module loading

*Recursos:*
- **Angular.io:** Architecture guide, NgModules
- **Books:** "Angular Architecture" por Mathieu De Wit
- **Medium:** Angular enterprise architecture
- **GitHub:** Angular architecture examples
- **Práctica:** Multi-feature enterprise application

#### Design Patterns en Angular
*Qué aprenderás:*
- Observer pattern: RxJS implementation
- Factory pattern: dynamic component creation
- Strategy pattern: configurable services
- Command pattern: action-based architecture
- Decorator pattern: method decorators, property decorators
- Adapter pattern: third-party integration

*Recursos:*
- **Books:** "Design Patterns in TypeScript"
- **Medium:** Angular design patterns series
- **Refactoring Guru:** TypeScript patterns
- **Práctica:** Extensible plugin system

### State Management Avanzado

#### NgRx Fundamentals
*Qué aprenderás:*
- Redux pattern: actions, reducers, store
- NgRx setup: `@ngrx/store`, `StoreModule.forRoot()`
- Actions: action creators, action types, payloads
- Reducers: pure functions, immutable updates
- Selectors: `createSelector`, memoization, reselect
- Store DevTools: debugging, time-travel

*Recursos:*
- **NgRx.io:** Official documentation
- **Udemy:** "NgRx (with NgRx Data)" por Mike Ryan
- **YouTube:** NgRx tutorials por Brandon Roberts
- **Práctica:** Shopping cart con NgRx, user management

#### NgRx Advanced
*Qué aprenderás:*
- Effects: `@ngrx/effects`, side effects management
- Entity: `@ngrx/entity`, normalized state, CRUD operations
- Router Store: `@ngrx/router-store`, navigation state
- Component Store: local state management
- Meta-reducers: higher-order reducers, logging, persistence
- Testing NgRx: actions, reducers, effects, selectors

*Recursos:*
- **NgRx.io:** Effects guide, Entity guide
- **GitHub:** NgRx example applications
- **Workshops:** NgRx Workshop materials
- **Práctica:** Complex data management, real-time updates

### Performance Optimization

#### Angular Performance
*Qué aprenderás:*
- Change detection optimization: `OnPush`, immutable data
- Lazy loading strategies: route-based, component-based
- Bundle optimization: tree shaking, dead code elimination
- Preloading strategies: custom preloading, network-aware
- Memory leak prevention: subscription management, detached components
- Performance profiling: Chrome DevTools, Angular DevTools

*Recursos:*
- **Web.dev:** Angular performance guide
- **YouTube:** Angular performance talks
- **Angular.io:** Performance guide
- **Tools:** webpack-bundle-analyzer, source-map-explorer
- **Práctica:** Performance audit y optimization

#### Advanced Optimization
*Qué aprenderás:*
- Virtual scrolling: `@angular/cdk/scrolling`
- Image optimization: lazy loading, responsive images
- Service Worker: `@angular/pwa`, caching strategies
- Code splitting: dynamic imports, chunk optimization
- Runtime performance: `ng-container`, structural directive optimization

*Recursos:*
- **Angular CDK:** Virtual scrolling guide
- **PWA:** Angular PWA documentation
- **Medium:** Advanced optimization techniques
- **Práctica:** High-performance data tables, PWA implementation

### Advanced Testing

#### Testing Strategies
*Qué aprenderás:*
- Testing pyramid: unit, integration, e2e ratios
- Page Object Model: e2e testing patterns
- Visual regression testing: Percy, Chromatic
- A11y testing: `@angular/cdk/a11y`, axe-core
- Performance testing: Lighthouse CI, bundle size monitoring
- Contract testing: API contract verification

*Recursos:*
- **Protractor/Cypress:** e2e testing guides
- **Testing Library:** Angular Testing Library
- **a11y:** Angular accessibility testing
- **Práctica:** Complete testing strategy implementation

### Angular CDK & Material

#### Component Development Kit
*Qué aprenderás:*
- Layout: flexbox utilities, grid system
- A11y: focus management, live announcer, aria
- Overlay: positioning, backdrop, scroll strategies
- Portal: dynamic content insertion
- Drag & Drop: sortable lists, transfer lists
- Virtual scrolling: performance optimization

*Recursos:*
- **Angular CDK:** Official documentation
- **Material.io:** Design principles
- **GitHub:** Angular CDK source code
- **Práctica:** Custom component library con CDK

---

## 🎓 Nivel Expertise

### Angular Internals

#### Advanced Framework Knowledge
*Qué aprenderás:*
- Angular compilation: Ivy renderer, AOT deep dive
- Change detection: zones, monkey patching, micro/macro tasks
- DI system: hierarchical injectors, injection tokens
- Module system: NgModules, lazy loading mechanics
- Custom decorators: metadata reflection, design patterns
- Angular Elements: custom elements, encapsulation

*Recursos:*
- **Angular:** Architecture deep dive
- **YouTube:** Angular team talks, ng-conf presentations
- **GitHub:** Angular source code analysis
- **Books:** "ng-book: The Complete Guide"
- **Práctica:** Custom framework features, Angular Elements

#### Micro-frontends con Angular
*Qué aprenderás:*
- Module Federation: Webpack 5 integration
- Single-SPA: framework integration patterns
- Angular Libraries: publishable libraries, ng-packagr
- Monorepo: Nx workspace, shared libraries
- Cross-application communication: custom events, shared state
- Independent deployments: CI/CD strategies

*Recursos:*
- **Nx.dev:** Monorepo management
- **Module Federation:** Webpack documentation
- **Medium:** Micro-frontends architecture
- **Práctica:** Multi-team micro-frontend architecture

### Advanced TypeScript

#### Type System Mastery
*Qué aprenderás:*
- Advanced generics: conditional types, mapped types
- Template literal types: string manipulation
- Utility types: creating custom utility types
- Branded types: nominal typing simulation
- Recursive types: tree structures, nested validation
- Type-level programming: computing types from types

*Recursos:*
- **TypeScript:** Advanced handbook sections
- **GitHub:** type-challenges repository
- **YouTube:** Matt Pocock TypeScript content
- **Práctica:** Type-safe API client generation

### Custom Libraries y Tools

#### Angular Library Development
*Qué aprenderás:*
- Library architecture: public API design, barrel exports
- ng-packagr: building, packaging, distribution
- Schematics: code generation, automated setup
- Testing libraries: TestBed configuration, peer dependencies
- Documentation: compodoc, interactive examples
- Versioning: semantic versioning, breaking changes

*Recursos:*
- **Angular.io:** Library guide
- **ng-packagr:** Documentation
- **Schematics:** Official guide
- **Práctica:** Publishable component library

#### Developer Tooling
*Qué aprenderás:*
- Custom schematics: template generation, code modification
- ESLint rules: Angular-specific rules, custom rules
- Webpack plugins: Angular-specific optimizations
- CLI extensions: custom commands, workspace extensions
- Build optimizations: custom builders, deployment tools

*Recursos:*
- **Angular DevKit:** Schematics y Architect
- **ESLint:** Rule development guide
- **Webpack:** Plugin development
- **Práctica:** Custom development tools suite

### Performance Expert

#### Advanced Performance Optimization
*Qué aprenderás:*
- Bundle analysis: dependency graphs, chunk optimization
- Runtime performance: memory profiling, CPU optimization
- Network optimization: HTTP/2, resource hints
- Critical rendering path: above-fold optimization
- Service Worker strategies: runtime caching, background sync
- Micro-frontend performance: shared dependencies, loading strategies

*Recursos:*
- **Web.dev:** Performance optimization
- **Chrome DevTools:** Performance profiling
- **Lighthouse:** CI integration
- **Práctica:** Performance consultancy approach

### Security Specialist

#### Angular Security
*Qué aprenderás:*
- XSS prevention: sanitization, trusted content
- CSRF protection: tokens, SameSite cookies
- CSP implementation: nonce-based, strict CSP
- Authentication patterns: OAuth2, JWT, refresh tokens
- Authorization: role-based, attribute-based access control
- Secure coding practices: input validation, output encoding

*Recursos:*
- **Angular.io:** Security guide
- **OWASP:** Top 10 web application security risks
- **Auth0:** Authentication best practices
- **Práctica:** Security audit y remediation

---

## 🏆 Nivel Master

### Innovation y Leadership

#### Framework Evolution
*Qué aprenderás:*
- Angular roadmap: upcoming features, RFC participation
- Community contribution: core team collaboration, open source
- Framework migration: version upgrades, breaking changes
- Alternative approaches: Standalone components, optional injectors
- Performance innovations: incremental compilation, smart bundling
- Future web standards: Web Components integration, ES modules

*Recursos:*
- **Angular:** GitHub issues, RFC discussions
- **Conferences:** ng-conf, AngularConnect presentations
- **Community:** Angular team blogs, community calls
- **Práctica:** RFC contributions, feature proposals

#### Technical Architecture Leadership
*Qué aprenderás:*
- Large-scale architecture: multi-team coordination, governance
- Technology strategy: framework selection, migration planning
- Performance culture: metrics, monitoring, optimization processes
- Developer experience: tooling, workflow optimization
- Code quality: review processes, automated quality gates
- Knowledge sharing: documentation, training, mentorship

*Recursos:*
- **Books:** "Building Evolutionary Architectures"
- **Conferences:** Architecture conferences, technical leadership
- **Communities:** CTO forums, architecture groups
- **Práctica:** Technical leadership en enterprise projects

### Research y Development

#### Advanced Web Technologies
*Qué aprenderás:*
- WebAssembly integration: performance-critical modules
- Web Components: Angular Elements evolution
- Progressive Web Apps: advanced PWA patterns
- WebXR: immersive web experiences
- Edge computing: CloudFlare Workers, edge-side rendering
- Performance monitoring: Real User Monitoring, Core Web Vitals

*Recursos:*
- **Web standards:** W3C specifications, WHATWG standards
- **Browser APIs:** MDN advanced APIs
- **Research papers:** Web technology research
- **Práctica:** Experimental web technology integration

#### Innovation Projects
*Qué aprenderás:*
- Proof of concepts: rapid prototyping, technology validation
- Research y development: emerging technology evaluation
- Patent applications: intellectual property development
- Conference speaking: knowledge sharing, thought leadership
- Technical writing: architecture decisions, technology evaluations
- Mentorship programs: senior developer development

*Recursos:*
- **Research:** Academic papers, technology conferences
- **Speaking:** Call for papers, presentation skills
- **Writing:** Technical blogs, architecture documentation
- **Práctica:** Innovation lab projects, thought leadership

### Business Impact

#### Strategic Technology Planning
*Qué aprenderás:*
- Technology roadmapping: long-term planning, risk assessment
- Cost-benefit analysis: technology investment evaluation
- Vendor evaluation: framework comparison, commercial solutions
- Team scaling: hiring strategies, skill development
- Process optimization: development workflows, quality processes
- Stakeholder communication: technical translation, executive reporting

*Recursos:*
- **Business:** Technology strategy frameworks
- **Leadership:** Technical leadership books, courses
- **Communication:** Stakeholder management, presentation skills
- **Práctica:** Strategic technology decisions, business impact measurement

---

## 🗂️ Proyectos Prácticos Progresivos

### Junior:
- **Personal Portfolio:** Routing básico, component communication
- **Todo Application:** CRUD operations, local storage, forms
- **Weather App:** HTTP client, async data, error handling

### Proficient:
- **E-commerce Catalog:** Reactive forms, HTTP interceptors, guards
- **Blog Platform:** Advanced routing, lazy loading, authentication
- **Dashboard App:** Charts integration, real-time data, state management

### Senior:
- **Enterprise CRM:** NgRx state management, testing suite, performance optimization
- **Component Library:** Angular CDK, documentation, publishing
- **Multi-tenant SaaS:** Micro-frontend architecture, advanced security

### Expertise:
- **Framework Extension:** Custom schematics, CLI plugins, build optimization
- **Performance Monitoring:** Real user monitoring, automated optimization
- **Developer Tools:** Custom linting rules, code generators, workflow automation

### Master:
- **Open Source Framework:** Community building, RFC authoring, conference speaking
- **Architecture Consulting:** Enterprise migration strategies, technology evaluation
- **Innovation Platform:** Emerging technology integration, research y development

---

## 📚 Habilidades Complementarias

### Testing Progression
- **Junior:** Unit testing básico, component testing
- **Proficient:** Integration testing, HTTP testing, forms testing
- **Senior:** E2E testing, visual regression, accessibility testing
- **Expertise:** Performance testing, contract testing, test automation
- **Master:** Testing strategy, quality culture, testing innovation

### DevOps Integration
- **Junior:** Angular CLI, local development setup
- **Proficient:** Build optimization, environment configuration
- **Senior:** CI/CD pipelines, automated deployment, monitoring
- **Expertise:** Infrastructure as code, containerization, scaling
- **Master:** DevOps culture, platform engineering, cloud architecture

### Accessibility Expertise
- **Junior:** Basic ARIA, semantic HTML, keyboard navigation
- **Proficient:** Screen reader testing, color contrast, focus management
- **Senior:** WCAG 2.1 compliance, accessibility automation
- **Expertise:** Accessibility consulting, inclusive design
- **Master:** Accessibility standards evolution, universal design

---

## 📚 Recursos Específicos Angular

### Documentación Oficial
- **Angular.io:** Guía completa y API reference
- **Angular CLI:** Command line interface documentation
- **Angular CDK:** Component Development Kit guide
- **Angular Material:** Official Material Design implementation

### Cursos Premium
- **Udemy:** "Angular - The Complete Guide" (Maximilian Schwarzmüller)
- **Frontend Masters:** Angular courses por experts
- **Pluralsight:** Angular learning path
- **egghead.io:** Angular courses por John Lindquist

### Comunidades y Blogs
- **Angular Blog:** Official Angular team blog
- **Angular University:** Comprehensive tutorials
- **Decoded Frontend:** Advanced Angular concepts
- **Medium:** Angular publication, community articles

### Herramientas de Desarrollo
- **Angular DevTools:** Browser extension para debugging
- **Nx:** Monorepo tools y development kit
- **Compodoc:** Documentation generation
- **Angular Console:** Visual interface para Angular CLI

### Libros Especializados
- "ng-book: The Complete Guide to Angular" - Nathan Murray
- "Angular Up and Running" - Shyam Seshadri
- "Angular Development with TypeScript" - Yakov Fain
- "Testing Angular Applications" - Jesse Palmer