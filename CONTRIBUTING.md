# Contributing

## Testing the web-based version
This extension is also supported in the VSCode Web Editor ([vscode.dev](https://vscode.dev)).

To test the web functionality locally, you can spin up a test VSCode web server by running the following commands in the root repository directory,

```bash
npm install
npx -y @vscode/test-web --browser none --extensionDevelopmentPath=.
```

then navigating to `localhost:3000` in your browser of choice.