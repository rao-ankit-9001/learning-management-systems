# React + Vite

### Setup Instruction

1. Clone the project.
``` 
    git clone https://github.com/rao-ankit-9001/learning-management-systems.git
```
2. Move into the directory.
```
    cd lms
```
3. Install Dependencies.
```
    npm install
```
4. Run the server.
```
    npm run dev
```

### Setup instructions for tailwindcss

[Tailwin official instruction Docs](https://tailwindcss.com/docs/installation)

1. Install tailwind css.
```
    npm install -D tailwindcss
```
2. Create tailwind config file.
```
    npx tailwind init 
```
3. Add file extensions to tailwind config file in the content property.
```
     content: ["./src/**/*.{html,js}"],
```
4. Add the tailwind directives at the top of 'index.css' file.
```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```


