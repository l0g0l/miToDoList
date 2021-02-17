Crea una TODO list que contenga lo siguiente:


Un formulario con input + botón
Un componente List que recorra listas de items
Un componente Item o Card que contenga cada TO DO
Botón CLEAR para borrar todas las tareas
Botón BORRAR, asociado a cada tarea, para poder borrar de manera independiente
Botón para hacer RESET de las tareas
Dar estilo CSS a los componentes con lo visto en clase para practicar
Flujo de la aplicación:

Nada más empezar tendremos un input par introducir txto
Hasta que no haya texto no aparecerá el botón ADD
Si hemos escrito algo en el input y hacemos click sobre el botón ADD, se añadirá un item debajo del input.
Cuando un item sea añadido, se borrará inmediatamente lo que habíamos escrito en el input y desaparecerá el botón ADD.
Se debe hacer una precarga de tareas de un JSON de datos
El botón de RESET mostrará de nuevo sólo las tareas obtenidas de la precarga de datos
la precarga de datos se debe hacer usando el lifecycle
Si pasados 20 segundos no envias la tarea que has escrito, se vaciará el input y desaparecerá ADD
Cuando haya sido añadida una tarea se mostrará durante 5 segundos el mensaje "tarea añadida" y luego desaparecerá
Validación: La tarea introducida en el input debe tener al menos 6 caracteres. En caso contrario debe aparecer un mensaje de error
TIP: usad el paquete de NPM UUID para manejar las keys de los diferentes elementos de la lista.



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
