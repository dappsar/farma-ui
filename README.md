# FarmaApp

## Introducción

Ésta aplicación se armo con el objetivo de .....

### ¿Qué 'tecnologías' usamos en el desarrollo de ésta app?

- [Git](https://git-scm.com/): Para la administración del código fuente.
- [Gitlab](https://gitlab.com/): Como repositorio de código fuente.
- [gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow): Como metodlogía de trabaja con el código fuente.
- [Redmine](https://www.redmine.org/): Para el seguimiento de tareas.
- [nvm](https://github.com/nvm-sh/nvm): Como instalador de nodeJs, para permitir múltiples versiones.
- [nodeJs](https://nodejs.org/es/): Como parte de la instalación básica para contener npm y yarn.
- [yarn](https://yarnpkg.com/lang/en/): Como gestor de paquetes. Aporta varias [ventajas](https://www.arquitecturajava.com/yarn-package-manager-y-node-js/) sobre el uso del (conocido) [npm](https://www.npmjs.com/).
- [React](https://es.reactjs.org/): Como biblioteca de Javascript para la interfaz de usuario.
- [Context API](https://es.reactjs.org/docs/context.html): Para la persistencia de estado de React. Es una alternativa a Redux.
- [Javascript](https://www.w3schools.com/js/): Como lenguaje principal de desarrollo.
- [html](https://www.w3schools.com/html/): Como lenguaje de desarrollo para las páginas web.
- [css](https://www.w3schools.com/css/): Como lenguaje de desarrollo para la aplicación de estilos a las páginas web.
- [pwa](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp?hl=es): Aplicación de escritorio que brinda una "experiencia" como si fuera una app móvil.
- [ServiceWorker](https://developers.google.com/web/fundamentals/primers/service-workers?hl=es): Patrón de diseño para página web progresivas.
- [Webpack](https://webpack.js.org/): Como un 'empaquetador de módulos' (bundler) para ejecución de tareas, conversión de formatos, servidor de desarrollo, carga y uso de módulos de todo tipo (como AMD, commonJs o ES2015). 
- [Babel](https://babeljs.io/): USando en compilación, para generación de archivos estándar de Javascript.
- [Jest](https://jestjs.io/): testing
- [Javascript Standar Styles](https://standardjs.com/readme-esla.html): Se usa en webpack con standard-loader, para centralizar los estánderes en el código y evitar tener archivos como: .eslintrc, .jshintrc, .jssrc.
- [Docker](https://www.docker.com/): Para integración contínua y despliegue contínuo
- [Heroku](https://dashboard.heroku.com/): https://elements.heroku.com/buildpacks/mars/create-react-app-buildpack
- [LightHouse Chrome Extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=es): Extensión específica de Chrome para usar con React.
- Azure

### Descripción de carpetas y archivos de la app

A continuación se describen las carpetas y archivos más importantes que conforman la app:


```bash
+---public
|       favicon.ico
|       index.html
|       logo192.png
|       logo512.png
|       manifest.json
|       robots.txt
|       
\---src
        App.css
        App.js
        App.test.js
        index.css
        index.js
        logo.svg
        serviceWorker.js
        setupTests.js
|   .gitignore
|   package.json
|   README.md
|   yarn.lock
```
        


---


## Armado de ambientes

### Local

Se describen a continuación los pasos para la instalación del ambiente local, asumiendo que el sistema operativo es Window. 

Paso 1: Editor de texto

Se recomienda tener como editor [Visual Studio Code](https://code.visualstudio.com/) con los siguientes plugins instalados:

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [The ES7 React/Redux/GraphQL/React-Native Snippets Extension](https://scotch.io/tutorials/the-best-react-extension-for-vs-code#toc-the-es7-react-redux-graphql-react-native-snippets-extension)
- [Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
- [JavaScript Standard Style](https://marketplace.visualstudio.com/items?itemName=chenxsan.vscode-standardjs)
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [Path IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Prettier Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [React Standard Style code snippets](https://marketplace.visualstudio.com/items/TimonVS.ReactSnippetsStandard)


El proyecto cuenta con una carpeta _.vscode_ la cuenta tiene un archivo, el cual establece parámetros de cofguración de vsCode al abrir el proyecto.

Paso 2: Git

Descargar el instalador de Git del siguiente enlace: https://git-scm.com/, ejecutarlo y seguir las indicaciones que aparezcan. 

Paso 3: NodeJs

Es recomendable instalar nodeJs con vnm, el cual permite tener varias versiones de nodeJs, npm y yarn a la vez.

Paso 4: Yarn

Ejecutar el siguiente comando:

```bash
npm i -g yarn
```

Paso 5: React

Ejecutar el siguiente comando:

```bash
npm i -g react-create-app
```

Paso 6: Instalación global de estándares de Javascript

Ejecutar dentro de la carpeta raíz de la aplicación

```bash
yarn add global standard
```

Paso 7: Dependencias de la aplicación

Ejecutar dentro de la carpeta raíz de la aplicación

```bash
yarn
```


### Nube

---

## Interacción con la aplicación

### ¿Cómo iniciar la app?

Paso 1: Descargar el código fuente con git

```bash
git clone <repo url>
```

Paso 2: Iniciar la aplicación

```bash
yarn start
```

### ¿Cómo Desarrollar en ésta app?


### ¿Cómo probar?

```bash
yarn test
```

---

## Documentación de referencia

Links a documentación de referencia de las tecnologías utilizadas.

### Webpack

- Stack Overflow. (2019). where is create-react-app webpack config and files?. [online] Available at: https://stackoverflow.com/questions/48395804/where-is-create-react-app-webpack-config-and-files [Accessed 14 Jan. 2020].

### PWA

- LePage, P. (2018). Tu primera Progressive Web App  |  Web Fundamentals  |  Google Developers. [online] Google Developers. Available at: https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp?hl=es [Accessed 14 Jan. 2020].

- Roebuck, K. (2017). YouTube. [online] Youtube.com. Available at: https://www.youtube.com/watch?v=4qpXnIAZ9Dk&list=PLYHcCSWbw4G6s7NVi2RK0TKd69PdB0sWe&index=1 [Accessed 14 Jan. 2020].

### Uso de context API en lugar de Redux

- Don, E. (2018). Use Hooks + Context, not React + Redux - LogRocket Blog. [online] LogRocket Blog. Available at: https://blog.logrocket.com/use-hooks-and-context-not-react-and-redux/ [Accessed 14 Jan. 2020].


