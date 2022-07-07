1---------------------
npm install eslint --save-dev

2---------------------
.eslintrc.js

rules: {
semi: ["error", "always"],
quotes: ["error", "double"],
indent: ["error", 4],
"eol-last": ["error", "never"],
"linebreak-style": 0,
}

3---------------------
VSC
"editor.codeActionsOnSave":
{ "source.fixAll.eslint": true },
