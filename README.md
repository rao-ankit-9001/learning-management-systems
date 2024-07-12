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

### Adding Plugins and dependencies
```
     npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```

### Configure auto import sort eslint

1. Install simple import sort.
```
    npm i eslint-plugin-simple-import-sort
```
2. Add rule in `.eslint.cjs`.
```
    'simple-import-sort/imports' : 'error'
```
3. Add simple-import sort plugin in `eslint.cjs`.
```
    plugins: [..., 'simple-import-sort']
```
4. To enable auto import sort on file save in vscode

    - Open `setting.json`
    - add the following config
```
    "editor.codeActionsOnSave": {
        "souce.fixAll.eslint : true
    }
```
