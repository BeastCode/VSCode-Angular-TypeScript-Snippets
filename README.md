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


# Pro Tip

You don't need to type any dashes: "ngrxr" -> "ng-rx-reducer" snippet


### TypeScript & Html Snippets

| Snippet | Description |
| ------- | ----------|
| ng-afterContentChecked | Lifecycle hook: Called after every check of the component's or directive's content |
| ng-afterContentInit | Lifecycle hook: Called after ngOnInit when the component's or directive's content has been initialized |
| ng-afterViewChecked | Lifecycle hook: Called after every check of the component's view. Applies to components only |
| ng-afterViewInit | Lifecycle hook: Called after ngAfterContentInit when the component's view has been initialized |
| ng-binding-oneway | Property: [property]=\"statement\" |
| ng-binding-twoway | Two-way data binding with the NgModel |
| ng-bootstraping | Bootstraping example |
| ng-button | A submit button element with a click event |
| ng-button-submit | A submit button element with a click event |
| ng-class | CSS class |
| ng-click | Click event |
| ng-component | Component with template and style urls |
| ng-component-inline | Component with inline Template and Styles |
| ng-controller | Use component instead. |
| ng-directive | Directive template |
| ng-directive-attribute | Attribute directive |
| ng-directive-css | CSS directive |
| ng-doCheck | Lifecycle hook: Called every time that the input properties of a component or a directive are checked |
| ng-event | Event: (event) = \"onEvent()\" |
| ng-filter | For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. |
| ng-for | For-loop directive |
| ng-for-index | For-loop directive with index |
| ng-for-li | For-loop directive with li element |
| ng-for-trackBy | For-loop directive with trackBy |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-if | If directive: *ngIf=\"statement\" |
| ng-import | import <module or component> from '<path>'; |
| ng-input | Class Input Property |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-module | App root module |
| ng-module-template | Module template |
| ng-ngOnChanges | Lifecycle hook: Called before any other lifecycle hook |
| ng-onDestroy | Lifecycle hook: Called before the instance is destroyed |
| ng-onInit | Lifecycle hook: Called after the constructor |
| ng-orderBy | For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. |
| ng-output | Class Output Event |
| ng-pipe | Pipe template |
| ng-pipe-async | Async pipe - Usage: observable_or_promise_expression &#x7c; async |
| ng-pipe-currency | Currency pipe - Usage: money &#x7c; currency:'EUR' |
| ng-pipe-date | Date pipe - Default format: 09/15/1971 |
| ng-pipe-date-custom | Date pipe - Format: \"MM/dd/yy\" = 09/15/71 |
| ng-pipe-date-full | Full date pipe - Format: Wednesday, September 15, 1971 |
| ng-pipe-date-short | Short date pipe - Format: 09/15/1971 |
| ng-pipe-decimal | Decimal pipe - Usage: number_expression &#x7c; decimal[:digitInfo] |
| ng-pipe-example | Angular pipe example |
| ng-pipe-json | Json pipe - Usage: object &#x7c; json |
| ng-pipe-lowercase | Lowercase pipe |
| ng-pipe-percent | Percent pipe - Usage: number_expression &#x7c; percent[:digitInfo] |
| ng-pipe-slice | Slice pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] |
| ng-pipe-uppercase | Uppercase pipe |
| ng-property | Property: [property]=\"statement\" |
| ng-repeat | Use ngFor instead. |
| ng-router | Router template |
| ng-router-link | Router link |
| ng-router-linkActive | Router active link |
| ng-router-outlet | Router outlet element |
| ng-router-outlet-name | Router outlet element with name |
| ng-router-routes | Routes to include in ngModule |
| ng-rx-action | ngRx Single action |
| ng-rx-actions | ngRx Actions class |
| ng-rx-module | ngRx Root Module |
| ng-rx-reducer | ngRx Reducer |
| ng-rx-util | ngRx Util |
| ng-service | Basic service |
| ng-show | Usage: Bind to the hidden property. |
| ng-src | Usage: Bind to the src property. |
| ng-style | CSS style |
| ng-switch | Switch template |
| ng-test-component-async | TODO |
| ng-test-component-synchronous | TODO |
| ng-test-directive | TODO |
| ng-test-pipe | Test a pipe |
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


##Feedback

Please send any feedback or suggestions to @Mike_BeastCode (Twitter) or create an issue on GitHub.


##Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data.


##License

MIT