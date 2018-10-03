{{- /* **NOTE: This  template comment will be removed by [`tmpl`].**
# typescript-react-webpack.tmpl

Template of [React] with [Babel] & [webpack] in  [TypeScript]

## How to use this template

```bash
# Install tmpl
go get -u github.com/nwtgck/tmpl

# Create a project from this template
tmpl new https://github.com/nwtgck/typescript-react-webpack.tmpl.git yourproject
```

Then, you will have `yourproject/` directory.

## What should you change after [`tmpl`] run?

- [src/index.html](src/index.html)
- [src/index.tsx](src/index.tsx)

[TypeScript]: https://www.typescriptlang.org/
[React]: https://reactjs.org/
[Babel]: https://babeljs.io/
[webpack]: https://webpack.js.org/
[`tmpl`]: https://github.com/nwtgck/tmpl

<!-- The following section is a template of README.md-->
*/ -}}
# {{.project_name}}

{{.description}}

## Build

```bash
npm install
npm run build
```

## Develop

```bash
npm install
npm start
```

Then, you can access to <http://localhost:8080/>, which will be loaded automatically if file changes detected.
