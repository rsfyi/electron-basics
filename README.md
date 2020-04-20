Electron Process Model

> 1. Electron reads the "main" entry in our package.json to determine which file to run.
> 2. "Main Process" - loads one or more "Rendered processes" using "BrowserWindow"
> 3. Each rendered process are independent of each other.

1. modify package.json - main - "app/main.js"
2. yarn add electron marked
