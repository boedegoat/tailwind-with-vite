# 🌈 Setup Tailwind CSS with Vite

1. Init `package.json`

   ```bash
    yarn init -y
   ```

1. Install these dev dependencies

   ```bash
    yarn add -D tailwindcss postcss autoprefixer vite
   ```

1. add dev script to `package.json`

   ```json
   "scripts": {
      "dev": "vite"
   }
   ```

1. Init tailwindcss with postcss to generate config file

   ```bash
    npx tailwindcss init -p
   ```

1. create your `main.css` file, then write this

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

1. create `index.html`, then link your `main.css` file into `<link />` tag

   ```html
   <head>
     <link rel="stylesheet" href="main.css" />
   </head>
   ```

1. run dev server

   ```bash
    yarn dev
   ```
