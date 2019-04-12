# angular-getting-started 

- Angular https://angular.io/
- Getting Started https://angular.io/guide/quickstart
- Angular CLI https://angular.io/cli
- Style Guide Recomendations https://angular.io/guide/styleguide
- Architecture Guide https://angular.io/guide/architecture
## build and run a simple Angular app

### Prerequisites

#### Node.js
- Angular requires Node.js version 8.x or 10.x
- To check your version, run node -v in a terminal/console window.
- To get Node.js, go to nodejs.org

#### npm package manager
Angular, the Angular CLI, and Angular apps depend on features and functionality provided by libraries that are available as npm packages. 
To download and install npm packages, you must have an npm package manager.
This Quick Start uses the npm client command line interface, which is installed with Node.js by default.
To check that you have the npm client installed, run npm -v in a terminal/console window.

### Step 1: Install the Angular CLI
You use the Angular CLI to create projects, generate application and library code, and perform a variety of ongoing development tasks such as testing, bundling, and deployment.

Install the Angular CLI globally.

`npm install -g @angular/cli`

### Step 2: Create a workspace and initial application
You develop apps in the context of an Angular workspace. A workspace contains the files for one or more projects. A project is the set of files that comprise an app, a library, or end-to-end (e2e) tests.

To create a new workspace and initial app project:
1. Run the CLI command ng new and provide the name my-app, as shown here:

    `ng new my-app`

2. The ng new command prompts you for information about features to include in the initial app project. Accept the defaults by pressing the Enter or Return key.

### Step 3: Serve the application
Angular includes a server, so that you can easily build and serve your app locally.
1. Go to the workspace folder (my-app).
2. Launch the server by using the CLI command ng serve, with the --open option.

    ```
    cd my-app
    ng serve --open
    ```
    
    The ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files.
    
    The --open (or just -o) option automatically opens your browser to http://localhost:4200

### Step 4: Edit your first Angular component
Components are the fundamental building blocks of Angular applications. They display data on the screen, listen for user input, and take action based on that input.

As part of the initial app, the CLI created the first Angular component for you. It is the root component, and it is named app-root.
1. Open ./src/app/app.component.ts.
2. Change the title property from 'my-app' to 'My First Angular App'. The browser reloads automatically with the revised title. That's nice, but it could look better.
3. Open ./src/app/app.component.css and give the component some style.
      ```
      h1 {
        color: #369;
        font-family: Arial, Helvetica, sans-serif;
        font-size: 250%;
      }
      ```

Tip: Most Angular guides include links to download example files and run live examples in Stackblitz https://stackblitz.com/ , so that you can see Angular concepts and code in action.

For more information about Angular project files and the file structure, see Workspace and project file structure (https://angular.io/guide/file-structure) .


### Next steps
- The Tour of Heroes tutorial (https://angular.io/tutorial) provides additional hands-on learning.
- The Architecture guide (https://angular.io/guide/architecture) describes key concepts such as modules, components, services, and dependency injection (DI). It provides a foundation for more in-depth guides about specific Angular concepts and features.

After the Tutorial and Architecture guide, you'll be ready to continue exploring Angular on your own through the other guides and references in this documentation set, focusing on the features most important for your apps.
