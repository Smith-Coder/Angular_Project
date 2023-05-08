## to install Angular CLI inside the machine
- $npm install -g @angular/cli@latest
- $ng new my-first-app --no-strict

## Including bootstrap inside angular
- $npm install --save bootstrap@3
- in angular.json file under styles add the bootstrap path

## Creating a new component via CLI
- ng generate servers
- ng g c servers

## DataBinding
- Communication between the TypeScript Code (Business Logic) and Template(HTML)
### Different ways of doing it
- DataBinding from TypeScript Code(Business Logic) to Template (HTML) >>> (Output data)
    - String Interpolation --> {{data}}
    - Property Binding --> [property]="data"
- from Template (HTML) to TypeScript Code (Business Logic) >>> when user React to (User) Events 
    - Event Binding --> (event)="expression"
- Combination of both:
    - Two-Way-Binding --> [(ngModel)]="data" 

- When to use StringInterpolation
    - if i want to output something in my template
- when to use PropertyBinding
    - if i want to change some property, be that of an html element or directives or component


## directives
- Directives are the instructions in the DOM 
- Component (directives with a template) is also a like a directive where we informed angular to include the Business logic and also template when a component selector is encountered
### Built-In Directives
#### Structural Directive
- *ngif --> * is required because ngif is a structural directive which changes the structure of the DOM, weather it adds or dosen't add an element.
        --> it can hold anything that returns true or false inside the quotes
#### Attribute directives
- unlike structural directives, attribute directives don't add or remove elements. they only change the element they were placed on.
- ngstyle
- ngclass
- ngfor

### New app
#### App planning
- (all are components)
- Root
    - Header
        - Shopping list(feature)
            - Shopping list
            - Shopping list edit
        - Recipe Book(feature)
            - Recipe list
            - Recipe item
            - Recipe Detail
- giving a structure or model 
  - ingredient class
  - Recipe class

- we should define how a recipe should look like by defining a structure or model in a class.
- 


         