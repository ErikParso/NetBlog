## Getting started

1. Install Angular Material and CDK
   - install ```npm install --save @angular/material @angular/cdk```
2. Install Animation support  
   - install ```npm install --save @angular/animations```
3. Import BrowserAnimationModule.  
4. Import Material component modules like MatButtonModule, MatCheckboxModule etc.  
Optionally you can create shared module for this purpose.  
5. Pick your component from [material.angular.io](http://material.angular.io) and add it to template.  
6. Include theme 
   - in styles.css add  ```@import "~@angular/material/prebuild-themes/pick-theme.css";```
7. Add gesture support  
   - install ```npm install --save hammerjs```  
   - add ```import 'hammerjs'``` in main.ts     
8. Add Material icons 
   - in index.html add  ```<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">```
   - use icon within component
    ```html
    <button mat-button>
       <mat-icon>face</mat-icon>
       Click me!
    </button>
    ```
