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

7.  Again in the `parent-component`. Add the `childExample` property in the selector of the `child-component` in the template of the `parent-component`, using property binding.

8.  Assign the `parentExample` as a value to the `childExample`.

9.  In the html of the `app-component`, add the selector of the `child` component.

Now run `npm start` and go to `http://localhost:4200/`.  
If you done everything correctly then the `child-component` should now display: `This is my child example: my parent value`

## Part 2 - passing data from the child to the parent (@Output & EventEmitter — event binding)

1.  Generate with the Angular CLI a `parent2-component` in the _app folder_ under `src`.

2.  In the `parent2-component`, add a string property called `parentExample` without a value. 

3.  Add a new method called `exampleMethodParent` with a `event` parameter. Inside this method, assign the `event` to the `parentExample`.

4.   Make use of inline templating in the `parent2-component` and display the `parentExample` value with interpolation.

5.  Generate with the Angular CLI a `child2-component` in the _app folder_ under `src`.

6.  In the `child2-component`, add a property with the name `outputExample` and as value an new event emitter with the type string. Also add the `@Output` decorator from Angular.

7.  Make another property which is a string called `childExample` with the following value: `My Angular 7 child value`.

8.  Create a method called `exampleMethodChild`, inside this method use the `outputExample` property and make use of the `emit` method of the event emitter. As parameter you pass the `childExample`.

9.  In the `parent2-component`, add the selector of the `child2-component`.

10.  Again in the `parent2-component`. Add the `outputExample` property in the selector of the `child2-component`. Using event binding.
Updat
Now run `npm start` and go to `http://localhost:4200/`.  
If you done everything correctly then the `parent2-component` should now display: `My Angular 7 child value` 

## Part 3 - refer to the child and access their properties inside the parent (@ViewChild & AfterViewInit)

to be described...  

## Serve

```cmd
// To install all dependencies
npm install

// To run the Angular project
npm start
```

