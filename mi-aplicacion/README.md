# step 1
## Create Client in Keycloak

first you need to create the client in keycloak <br/> 
primero se necesita crear un cliente en keycloak <br/> 

![image](https://user-images.githubusercontent.com/12897488/160495090-f756db06-2399-425e-a45a-10c1951325aa.png)

then configure the client  <br/> 
luego configurar el cliente <br/>  
![image](https://user-images.githubusercontent.com/12897488/160495352-d8cc7f29-150e-40e6-8771-a071177bd392.png)

then press the save button <br/>
luego presionar el boton guardar <br/>
![image](https://user-images.githubusercontent.com/12897488/160495852-a97d0588-3904-407d-afd3-61461e0b76d3.png)

# step 2
## MiAplicacion
This project was built with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.0.
Este proyecto se generó con [Angular CLI](https://github.com/angular/angular-cli) versión 13.3.0.

## Install keycloak-angular keycloak-js / instalar keycloak-angular keycloak-js
   [npm keycloak-angular](https://www.npmjs.com/package/keycloak-angular)<br/>
   [npm keycloak-js](https://www.npmjs.com/package/keycloak-js)<br/>
   
   npm install keycloak-angular keycloak-js
   
```console
ecollado1@srvMachine:~$ npm install keycloak-angular keycloak-js
```

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. <br/>
               para construir el proyecto. Los artefactos de compilación se almacenarán en el directorio `dist/`.

### compile the project / compilar el proyecto

```console
ecollado1@srvMachine:~$ ng build

Node.js version v17.8.0 detected.
Odd numbered Node.js versions will not enter LTS status and should not be used for production. For more information, please see https://nodejs.org/en/about/releases/.
✔ Browser application bundle generation complete.
✔ Copying assets complete.
✔ Index html generation complete.

Initial Chunk Files           | Names         |  Raw Size | Estimated Transfer Size
main.c0ccb79935143cde.js      | main          | 215.46 kB |                58.00 kB
polyfills.8b245e5bebea2570.js | polyfills     |  33.03 kB |                10.62 kB
runtime.04a9726dfa065481.js   | runtime       |   1.06 kB |               598 bytes
styles.ef46db3751d8e999.css   | styles        |   0 bytes |                       -

                              | Initial Total | 249.55 kB |                69.21 kB

Build at: 2022-03-28T22:04:41.894Z - Hash: 5ac5897a1e13566d - Time: 10677ms

Warning: /home/collado/workspace-angular/keycloak-angular-application/mi-aplicacion/node_modules/keycloak-angular/fesm2015/keycloak-angular.mjs depends on 'keycloak-js'. CommonJS or AMD dependencies can cause optimization bailouts.
For more info see: https://angular.io/guide/build#configuring-commonjs-dependencies

```

## Development server / Despliegue servidor desarrollo

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

```console
ecollado1@srvMachine:~$ ng serve --host=0.0.0.0
Node.js version v17.8.0 detected.
Odd numbered Node.js versions will not enter LTS status and should not be used for production. For more information, please see https://nodejs.org/en/about/releases/.
Warning: This is a simple server for use in testing or debugging Angular applications
locally. It hasn't been reviewed for security issues.

Binding this server to an open connection can result in compromising your application or
computer. Using a different host than the one passed to the "--host" flag might result in
websocket connection issues. You might need to use "--disable-host-check" if that's the
case.
✔ Browser application bundle generation complete.

Initial Chunk Files   | Names         |  Raw Size
vendor.js             | vendor        |   2.16 MB | 
polyfills.js          | polyfills     | 294.80 kB | 
styles.css, styles.js | styles        | 173.23 kB | 
main.js               | main          |  17.35 kB | 
runtime.js            | runtime       |   6.65 kB | 

                      | Initial Total |   2.64 MB

Build at: 2022-03-28T22:28:08.216Z - Hash: 54a26f71fd73576e - Time: 3754ms

Warning: /home/collado/workspace-angular/keycloak-angular-application/mi-aplicacion/node_modules/keycloak-angular/fesm2015/keycloak-angular.mjs depends on 'keycloak-js'. CommonJS or AMD dependencies can cause optimization bailouts.
For more info see: https://angular.io/guide/build#configuring-commonjs-dependencies



** Angular Live Development Server is listening on 0.0.0.0:4200, open your browser on http://localhost:4200/ **


✔ Compiled successfully.
```
## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
