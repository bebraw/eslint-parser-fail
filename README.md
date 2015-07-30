# ESLint fails to warn that parser is missing

1. npm install
2. npm run lint - This should complete without failures
3. rm -rf node_modules/babel-eslint/
4. npm run lint - This should give an error about missing parser but it doesn't
