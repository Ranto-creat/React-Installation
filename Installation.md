# React Installation without Vue

```PowerShell
npm create vite@latest
```

## Configuration
```PowerShell
√ Project name: ... <your project-name>
√ Package name: ... <your package-name>
√ Select a framework: » React
√ Select a variant: » JavaScript
```

> **``cd <your package-name>``**

## Install all dependencies

```npm install```

## Run the Project: 

```npm run dev```

### Installation completed successfully [image](./localHost.png)

>> Link our vite site [click here](https://vitejs.dev/guide/)

## Install Tailwinds in React

``npm install -D tailwindcss postcss autoprefixer``
``npx tailwindcss init -p``

## Configurer Tailwind CSS

> tailwind.config.js

````jsx
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

````

> src/index.css

````jsx
@tailwind base;
@tailwind components;
@tailwind utilities;
````
