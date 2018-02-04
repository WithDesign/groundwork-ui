# Groundwork UI
Groundwork UI is a lightweight Scss framework composed of a base setup of styles and a library of UI components to create any site.

## Instillation:

Add to your package.json:
```
"dependencies": {
  "groundwork-ui": "git+ssh://git@github.com/WithDesign/groundwork-ui.git#TAG",
},
```

Add to your main SCSS:
```
@import 'PATH-TO-NODE_MODULES/node_modules/groundwork-ui/scss/main';
```

Add the settings variable to your project to override the default settings:

**NOTE:: This variable must be imported before the `Groundwork UI` package Scss.**

```
$user-defined-settings: (
  colors: (
    brand: (
      primary: #fff,
    ),
  ),
);
```
