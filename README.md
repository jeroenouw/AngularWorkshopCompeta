# Angular Workshop Competa IT

## Share component data with other components

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

## Part 1 - passing data from the parent to the child (@Input — property binding)

1.  Generate with the Angular CLI a `parent-component` in the _app folder_ under `src`.

2.  Add a string property with the name `parentExample` and the value `my parent value` in the generated `parent-component`.

3.  Generate with the Angular CLI a `child-component` in the _app folder_ under `src`.

4.  Add a string property called `childExample` with the Angular's `@Input` decorator in the generated `child-component`.

5.  Make use of inline templating in the `child-component` and display the `childExample` value with interpolation. Also place in front of the interpolation: `This is my child example: `

6.  In the `parent-component`, make use of inline templating and place the selector of the `child-component` inside this template.

7.  Add the `childExample` property in the selector of the `child-component` in the template of the `parent-component`, using property binding.

8.  Assign the `parentExample` as a value to the `childExample`.

9.  In the html of the `app-component`, add the selector of the `child` component.

If you done everything correctly then the `child-component` should now display: `This is my child example: my parent value`

## Part 2 - passing data from the child to the parent (@Output & EventEmitter — event binding)

to be described...  

## Part 3 - refer to the child and access their properties inside the parent (@ViewChild & AfterViewInit)

to be described...  

## Serve

```cmd
// To install all dependencies
npm install

// To run the Angular project
npm start
```

