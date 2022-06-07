# ExpApp


Prerequisite :
  1. angular-cli-ghpages <npm i angular-cli-ghpages -g>
  
Step:
  1. Create github page setup on repository by go to Settings => Pages. On Source select branch main and docs folder.
  2. In local repo, change angular.json file on outputPath field value by 'docs'.
  3. Run command 'ng build -c production --base-href https://febrianobramantyo.github.io/exp-angular-deploy-githubpages/ && git add . && git commit -m "init commit" && git push origin main'.
  4. Open app by got to https://febrianobramantyo.github.io/exp-angular-deploy-githubpages/

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
