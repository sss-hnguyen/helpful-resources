# Angular

Angular provides a command-line tool called 'ng'

Install it with npm globally

```
npm install @angular/cli -g
```

## Create a new app

The following command will prompt for setup questions and set up a new folder.

```
ng new my-new-angular-app --style=scss --routing=true
```

If tests will not be defined and maintained, you can pass this option to avoid test creation.
`--skipTests=true`

See [Angular Testing Guide](https://angular.io/guide/testing)

## Common Commands

Generating parts of your angular app is made easy with the command line. Note the letters and the results.
- m for module
- c for component
- s for service

Create a new module

`ng g m optional-subfolder/some-module`

Create a new component

`ng g c optional-subfolder/some-component`

Create a new service

`ng g c optional-subfolder/some-service`

See [Angular CLI](https://angular.io/cli)
