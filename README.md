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

![ngForSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngForSnippet.gif)


### TypeScript & Html Snippets

| Snippet | Description |
| ------| -----------|
| ng-AfterContentChecked |  |
| ng-afterContentInit |  |
| ng-afterViewChecked |  |
| ng-afterViewInit |  |
| ng-binding-oneway |  |
| ng-binding-twoway | Property and Event: [(ngModel)]=\"heroName\" |
| ng-bootstraping |  |
| ng-class |  |
| ng-click | Click event |
| ng-component | Angular 2+ Component Snippet |
| ng-component-inline | Angular 2+ Component Inline Snippet |
| ng-controller | Use component instead. |
| ng-directive |  |
| ng-doCheck |  |
| ng-event | Event: (event) = \"onEvent()\" |
| ng-filter | For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. |
| ng-for | For-loop Directive Angular 2+ |
| ng-for-index | For-loop Directive Angular 2+ |
| ng-for-li | For-loop Directive with li element |
| ng-for-trackBy | For-loop Directive Angular 2+ |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-if | If Directive: *ngIf=\"statement\" |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-module |  |
| ng-ngOnChanges |  |
| ng-onDestroy |  |
| ng-onInit |  |
| ng-orderBy | For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. |
| ng-pipe |  |
| ng-pipe-async | Usage: observable_or_promise_expression | async |
| ng-pipe-currency | Usage: money | currency:'EUR' |
| ng-pipe-date | Format: 09/15/1971 |
| ng-pipe-date-custom | Format: \"MM/dd/yy\" = 09/15/71 |
| ng-pipe-date-full | Format: Wednesday, September 15, 1971 |
| ng-pipe-date-short | Format:  09/15/1971 |
| ng-pipe-decimal | Usage: number_expression | decimal[:digitInfo] |
| ng-pipe-example | Angular  Pipe Example |
| ng-pipe-json | Usage: object | json |
| ng-pipe-lowercase |  |
| ng-pipe-percent | Usage: number_expression | percent[:digitInfo] |
| ng-pipe-slice | Usage: array_or_string_expression | slice:start[:end] |
| ng-pipe-uppercase |  |
| ng-property | Property: [property]=\"statement\" |
| ng-repeat | Use ngFor instead. |
| ng-router |  |
| ng-router-link |  |
| ng-router-linkActive |  |
| ng-router-linkWithHref | TODO |
| ng-router-outlet |  |
| ng-router-routes | TODO |
| ng-rx | TODO |
| ng-rx2 | TODO |
| ng-service | Angular 2+ Service |
| ng-show | Usage: Bind to the hidden property. |
| ng-src | Usage: Bind to the src property. |
| ng-style |  |
| ng-switch |  |
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