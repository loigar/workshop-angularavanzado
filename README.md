


# Introducción 

Workshop de Angular Avanzado: Rendimiento, arquitectura, buenas prácticas

# Requisitos

- Visual Studio Code  
- Node 12.17.0
- Angular CLI: 10.0.1 
*comprobable mediante* `ng --version`

# Temario

 1. Detección del cambio en Angular
       - Comunicación entre componentes
       - Estrategia de detección de cambios
 2. Navegación y datos
	   - Ciclo de vida en Angular
       - Environment
       - Router
       - Lazy loading
       - Rutas parametrizadas
       - Ejecuciones previas a la navegación: resolvers y guards
 3. Tratamiento asíncrono de datos con RxJS
       - Operadores multillamada con RxJS (flatMap, forkJoin y similares)
       - Pipe async
       - Store reactivo para comunicación asíncrona global. Patrón redux
 4. Tips
 
# Grabación
_proximamente_
  - Sesión [**02.06.2022**]()

# Material de apoyo
_proximamente_
- [Presentación]()
- [Seed](): Proyecto de partida para la realización de la práctica

# Preguntas de auto-evaluación

 - La detección del cambio por defecto en Angular es OnPush [Y/N]
 - La detección del cambio por defecto sólo tiene en cuenta las referencias y no el contenido de los objetos [Y/N]
 - El método ngOnInit es el primer método en ejecutarse dentro del ciclo de vida de Angular [Y/N]
 - El router es un componente Angular que carga contenido en su interior [Y/N]
 - No se puede reutilizar un componente para que cargue una información u otra en función de un parámetro de la url [Y/N]
 - Los resolvers permiten obtener datos antes de la carga del componente [Y/N]
 - El operador forkJoin tiene como principal utilidad la legibilidad del código, pero no aporta ninguna ventaja en la obtención de datos vía http [Y/N]
 - "Única fuente de datos", "estado de sólo lectura", "cambios mediante funciones puras" y "uso de objetos con tipos simples" son los principios del patrón Redux [Y/N]

# Autogenerated additional info

## AngularApp

This project was generated with version 10.0.2

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
