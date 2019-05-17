# Internal training repository - Angular
## References
* Part One - https://www.youtube.com/watch?v=AR1tLGQ7COs
* Part Two - https://www.youtube.com/watch?v=OrCdt865WOg


### Crear un proyecto nuevo

ng new admin                    // Si el proyecto se llama admin

### Consideraciones

* Which stylesheet format would you like to use? (Use arrow keys): CSS o SASS.
* Would you like to add Angular routing? (y/N): y para habilitar la configuración de ruteo por defecto de Angular.

### Instalar Bootstrap una vez inicializado el proyecto con angular-cli

npm install bootstrap jquery popper.js


## Estructura de la aplicación
Toma app como componente base

admin
-- node_modules
-- src
-- -- components
-- -- app.component.html        // HTML base
-- -- app.component.ts          // Controlador del componente base
-- -- app.component.sass        // Estilos base
-- -- app.component.spec.ts     // Testing
-- -- app-routing.module.ts     // Maneja el ruteo de la aplicación
-- -- app.module.ts             // Centraliza la carga de modulos para que puedan ser usados en la app


