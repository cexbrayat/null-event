# NullEvent

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.0-rc.0.

## Template

```html
<button (click)="title = null">Cancel</button>
```

## Error

With `fullTemplateTypeCheck` throws:

```
ERROR in src/app/app.component.html:1:18 - error TS7011: Function expression, which lacks return-type annotation, implicitly has an 'any' return type.

1 <button (click)="title = null">Cancel</button>
                   ~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.
```