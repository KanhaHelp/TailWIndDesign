1. npm init 

2. npm install -D tailwindcss postcss autoprefixer vite

3. npx tailwindcss init -p

4. Create a css file - main.css (Anything u can named )
    paste the below code to main.css

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

5. In your tailwind.config.js file, replaced content: [] with content: ["*"]

6. link your css file to html file 

    <link rel="stylesheet" href="main.css">

7. add below code to your package.json

    "scripts": {
        "start" : "vite"
    },

8. Run npm run start to start the development server 


