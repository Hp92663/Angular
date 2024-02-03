


![Logo](https://angular.io/assets/images/logos/angular/logo-nav@2x.png)

## Installation

Install Angular CLI globally

> [!IMPORTANT]

```bash
  npm install -g @angular/cli
```

Install my-project

```bash
  ng new my-project --no-standalone --no-strict
  cd my-project
```

Run project

```bash
  ng serve
```

Create new `component`

```bash
  ng generate component <component-name>
```

Create new `module`

```bash
  ng generate module <module-name>
```

Create new `class`

```bash
  ng generate class <class-name>
```

Create new `service`

```bash
  ng generate service <service-name>
```

Create new `component` with `inline-template`

```bash
  ng generate component <component-name> --inline-template
```

Create new `component` with `inline-style`

```bash
  ng generate component <component-name> --inline-style
```

## 01_module

* module is a feature of a 

* It can include components, services, pipes, route, API call etc.

* Whenever you can creating new component in a module. It can automatically `declare` the component name in `example.module.ts`. file 

* When component can use in any other component so that first of all `export` the component in  `example.module.ts`.



```javascript
  exports : [
    ExampleComponent
  ]
```

* when we can use component in any another component that can define/declare using  `selector`

## 02_data binding

### Event binding

`app.module.ts`

```javascript

  addTwo(name)
  {
    alert(name)
  }
```
`app.template.html`

```javascript
  <button (click)="addTwo("Hiren")>submit</button>
```

* Other Events
 > keyup
 > keydown
 > blur
 > input

 * Mouse Event
 > mouseleave
 > mouseover









> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
