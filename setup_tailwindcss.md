npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init

1---------------------
postcss.config.js

module.exports = {
plugins: {
tailwindcss: {},
autoprefixer: {},
}
}

2---------------------
tailwind.config.js

module.exports = {
content: ["./src/**/*.{html,js}"],
theme: {
extend: {},
},
plugins: [],
}

3---------------------
main.css

@tailwind base;
@tailwind components;
@tailwind utilities;

4---------------------

<link href="/dist/main.css" rel="stylesheet">
