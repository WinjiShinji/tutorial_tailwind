# Tailwind Notes

## Install

1. npm install -D tailwindcss

2. npx tailwindcss init

3. tailwind.config.js:

   > content: [build dir path]

4. input.css:

   > - @tailwind base;
   > - @tailwind components;
   > - @tailwind utilities;

5. npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

6. index.html:
   > - `<link href="./output.css" rel="stylesheet">`
