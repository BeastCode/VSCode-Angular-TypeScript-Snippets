# VSCode Angular TypeScript & Html Snippets
Visual Studio Code TypeScript and Html snippets and code examples for Angular 2+

# Important
This extension is optimized for devlopers that use Angular 2+ and are no longer using Angular 1.
If you type in Angular 1 keywords, it will suggest an Angular 2 solutions. 
This is by design and ment to help developers learn how Angular 1 concepts and techniques map to Angular 2+

See example below for ng-repeat and ng-click:

![ngRepeatSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngRepeatSnippet.gif)


All code snippets are based on and follow the Angular style guide https://angular.io/docs/ts/latest/guide/style-guide.html and can be 

# Usage

All snippets starts with "ng-".
Multiple snippets come in multiple variations. For instance when you want to create a new component you can choose between having the template and css inline or not:
* ng-component
* ng-component-inline


### ng-component

![ngComponentSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngComponentSnippet.gif)

### ng-for

ng-for currently has even more variations, so make sure you pick the one you want before you press enter:
* ng-for
* ng-for-index
* ng-for-li
* ng-for-trackBy

![ngForSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngForSnippet.gif)


### TypeScript & Html Snippets

| Snippet | Description |
| ------| -----------|
| ng-afterContentChecked | Lifecycle Hook: Called after every check of the component's or directive's content |
| ng-afterContentInit | Lifecycle Hook: Called after ngOnInit when the component's or directive's content has been initialized |
| ng-afterViewChecked | Lifecycle Hook: Called after every check of the component's view. Applies to components only |
| ng-afterViewInit | Lifecycle Hook: Called after ngAfterContentInit when the component's view has been initialized |
| ng-binding-oneway | TODO |
| ng-binding-twoway | Property and Event: [(ngModel)]=\"heroName\" |
| ng-bootstraping | Bootstraping Example |
| ng-class | CSS Class |
| ng-click | Click event |
| ng-component | Component with Template and Style Urls |
| ng-component-inline | Component with Template and Style Inline |
| ng-controller | Use component instead. |
| ng-directive | Directive Template |
| ng-directive-attribute | Attribute Directive |
| ng-directive-css | CSS Directive |
| ng-doCheck | Lifecycle Hook: Called every time that the input properties of a component or a directive are checked |
| ng-event | Event: (event) = \"onEvent()\" |
| ng-filter | For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. |
| ng-for | For-loop Directive |
| ng-for-index | For-loop Directive with index |
| ng-for-li | For-loop Directive with li element |
| ng-for-trackBy | For-loop Directive with trackBy |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-if | If Directive: *ngIf=\"statement\" |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-module | App root mudule |
| ng-module-template | Module Template |
| ng-ngOnChanges | Lifecycle Hook: Called before any other lifecycle hook |
| ng-onDestroy | Lifecycle Hook: Called before the instance is destroyed |
| ng-onInit | Lifecycle Hook: Called after the constructor |
| ng-orderBy | For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. |
| ng-pipe | Pipe Template |
| ng-pipe-async | Async Pipe - Usage: observable_or_promise_expression &#x7c; async |
| ng-pipe-currency | Currency Pipe - Usage: money &#x7c; currency:'EUR' |
| ng-pipe-date | Date Pipe - Default format: 09/15/1971 |
| ng-pipe-date-custom | Date Pipe - Format: \"MM/dd/yy\" = 09/15/71 |
| ng-pipe-date-full | Full Date Pipe - Format: Wednesday, September 15, 1971 |
| ng-pipe-date-short | Short Date Pipe - Format: 09/15/1971 |
| ng-pipe-decimal | Decimal Pipe - Usage: number_expression &#x7c; decimal[:digitInfo] |
| ng-pipe-example | Angular  Pipe Example |
| ng-pipe-json | Json Pipe - Usage: object &#x7c; json |
| ng-pipe-lowercase | LowerCase Pipe |
| ng-pipe-percent | Percent Pipe - Usage: number_expression &#x7c; percent[:digitInfo] |
| ng-pipe-slice | Slice Pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] |
| ng-pipe-uppercase | UpperCase Pipe |
| ng-property | Property: [property]=\"statement\" |
| ng-repeat | Use ngFor instead. |
| ng-router | Router Template |
| ng-router-link | Router Link |
| ng-router-linkActive | Router Active Link |
| ng-router-linkWithHref | TODO |
| ng-router-outlet | Router Outlet Element |
| ng-router-routes | Routes to include in Module |
| ng-rx-action | Single ngRx Action |
| ng-rx-actions | ngRx Actions |
| ng-rx-reducer | ngRx Reducer |
| ng-rx-util | ngRx Util |
| ng-service | Basic Service |
| ng-show | Usage: Bind to the hidden property. |
| ng-src | Usage: Bind to the src property. |
| ng-style | CSS Style |
| ng-switch | Switch Template |
| ng-test-component | TODO |
| ng-test-directive | TODO |
| ng-test-pipe | TODO |
| ng-test-service | TODO |


##Installation (Mac)

1. Launch VS Code 
2. Quick Open (⌘+P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


##Installation (Windows, Linux)

1. Launch VS Code 
2. Quick Open (Ctrl-Shift-P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


##Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data.


##License

MIT