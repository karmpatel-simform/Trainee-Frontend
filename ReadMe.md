# Getting Started with Trainee-Frontend

This project was bootstrapped with [Vite React App](https://vite.dev/guide/).

## Table of Contents

- [Requirements](#Requirements)
- [Starting Setup Steps](#starting-setup-steps)
- [Available Scripts](#available-scripts)
  - [npm run dev](#npm-run-dev)
  - [npm run lint](#npm-run-lint)
  - [npm run build](#npm-run-build)
  - [npm run preview](#npm-run-preview)
 
## Requirements

Before you begin, you will need **Node.js** and **Yarn** installed on your system.

### Node.js Installation

- **Windows**: Download and install from the [Node.js website](https://nodejs.org/).
- **Ubuntu**: Run the following commands:

  ```bash
  $ sudo apt install nodejs
  $ sudo apt install npm
  ```

To check if Node.js and npm are installed, run:

```bash
$ node --version
$ npm --version
```

### Yarn Installation

After installing Node.js, you also need **Yarn**. Install it globally with:

```bash
$ npm install -g yarn
```


## Starting Setup Steps

Follow these steps to get your development environment up and running.

1. **Clone the repository**:
   If you haven’t cloned the repository yet, run the following command:
   ```bash
   git clone https://github.com/karmpatel-simform/Trainee-Frontend.git
   ```

2. **Install dependencies**:
   After cloning the repository, navigate into the project directory and install the necessary dependencies:
   ```bash
   cd trainee-frontend
   npm install
   ```

3. **Start the development server**:
   Once dependencies are installed, you can start the Vite development server:
   ```bash
   npm run dev
   ```
   This will run the app in development mode and you can view it in your browser at [http://localhost:5173](http://localhost:5173).

---

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run lint`

Runs the linter on your codebase to check for any potential issues.\
This will output warnings or errors in the console if there are any code quality or formatting issues.

### `npm run build`

Builds the app for production to the `dist` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://vitejs.dev/guide/static-deploy.html) for more information.

### `npm run preview`

Preview the production build locally. This is useful to verify your production build before deploying it.

