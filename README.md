[![Version](https://vsmarketplacebadge.apphb.com/version/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

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

All Angular snippets starts with "ng-".
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

### Angular Material
All Material snippets starts with "m-" and there are now over 30 Material snippets in this package.

# Pro Tip

You don't need to type any dashes: "ngrxr" -> "ng-rx-reducer" snippet


### TypeScript & Html Snippets

| Snippet | Description |
| ------- | ----------|
|       "\tselector: '${1:}-${2:name}', | ng-component-inline |
|       "\tselector: '[${1:}${2:Name}]', | ng-service |
| A button element with a click event | ng-import |
| A lightning talk by Gary Bernhardt from CodeMash 2012. ng-wat talk by Shai Reznik in 2015 | ng-conf |
| A submit button element with a click event | ng-button |
| Angular pipe example | ng-pipe-uppercase |
| App root module | ng-pipe |
| Async pipe - Usage: observable_or_promise_expression &#x7c; async | ng-ngOnChanges |
| Basic service | ng-bootstraping |
| Bootstraping example | ng-module |
| CSS class | ng-style |
| CSS style | ng-switch |
| CanActivate Guard Route | ng-route-guard-canactivatechild |
| CanActivateChild Route | ng-route-guard-resolve |
| CanDeactivate Guard Route | ng-rx-util |
| CanLoad Guard Route | ng-route-guard-candeactivate |
| Circular Material button with a transparent background | m-button-fab |
| Circular button w/ elevation. | m-button-fab-mini |
| Class Input Property | ng-output |
| Class Output Event | ng-binding-oneway |
| Click event | ng-controller |
| Component with inline Template and Styles |       "\tselector: '${1:}-${2:name}', |
| Currency pipe - Usage: money &#x7c; currency:'EUR' | ng-pipe-json |
| Date pipe - Default format: 09/15/1971 | ng-pipe-date-custom |
| Date pipe - Format: \"MM/dd/yy\" = 09/15/71 | ng-pipe-date-short |
| Decimal pipe - Usage: number_expression &#x7c; decimal[:digitInfo] | ng-pipe-slice |
| Event: (event) = \"onEvent()\" | ng-input |
| Feature Module | ng-module-root |
| Flex Layout Align Property | ng-fx-layout-gap |
| Flex Layout Column | ng-fx-col-reverse |
| Flex Layout Gap Property | ng-fx-row-reverse |
| Flex Layout Import | ng-fx-row |
| Flex Layout Item with fxFlexAlign | ng-fx-item-fill |
| Flex Layout Item with fxFlexFill | m-toolbar |
| Flex Layout Item with fxFlexOffset | ng-fx-item-order |
| Flex Layout Item with fxFlexOrder | ng-fx-item-align |
| Flex Layout Item | ng-fx-item-offset |
| Flex Layout Property | ng-fx-layout-align |
| Flex Layout Reverse Column | ng-fx-item |
| Flex Layout Reverse Row | ng-fx-col |
| Flex Layout Row | ng-fx-layout |
| For performance reasons, no comparable pipe exists in Angular 2. Do all your filtering in the component. If you need the same filtering code in several templates, consider building a custom pipe. | ng-button-submit |
| For performance reasons, no comparable pipe exists in Angular 2. Instead, use component code to order or sort results. If you need the same ordering or sorting code in several templates, consider building a custom pipe. | ng-filter |
| For-loop directive with index | ng-for-trackBy |
| For-loop directive with li element | ng-for-index |
| For-loop directive with trackBy | ng-class |
| For-loop directive | ng-for-li |
| Full date pipe - Format: Wednesday, September 15, 1971 | ng-pipe-percent |
| Http observable get & post request | ng-debug |
| Http observable get request | ng-httpClient-get |
| HttpClient observable get request | ng-http-get-post |
| If directive: *ngIf=\"expression\" | ng-if-else |
| Interpolation: {{ interpolation }} | ng-repeat |
| Json pipe - Usage: object &#x7c; json | ng-pipe-async |
| Lifecycle hook: Called after every check of the component's or directive's content | ng-afterViewInit |
| Lifecycle hook: Called after every check of the component's view. Applies to components only | ng-onDestroy |
| Lifecycle hook: Called after ngAfterContentInit when the component's view has been initialized | ng-afterViewChecked |
| Lifecycle hook: Called after ngOnInit when the component's or directive's content has been initialized | ng-afterContentChecked |
| Lifecycle hook: Called after the constructor | ng-doCheck |
| Lifecycle hook: Called before any other lifecycle hook | ng-onInit |
| Lifecycle hook: Called before the instance is destroyed | wat |
| Lifecycle hook: Called every time that the input properties of a component or a directive are checked | ng-afterContentInit |
| Lowercase pipe | ng-pipe-titlecase |
| Material Basic Card | m-radiobutton |
| Material Checkbox | m-datepicker |
| Material Chip List | m-chip-list-stacked |
| Material Chip Stacked List | m-chip |
| Material Chip | m-select |
| Material Datepicker | m-input |
| Material Determinate Spinner | m-spinner-indeterminate |
| Material Font Awesome Icon | m-button |
| Material Grid List | m-paginator |
| Material Input Textbox | m-chip-list |
| Material List Item | m-tab-group |
| Material List ngFor | m-list-item |
| Material List | m-list-ngfor |
| Material Paginator | m-spinner |
| Material Radio Button Option | m-checkbox |
| Material Radio Button | m-radiobutton-option |
| Material SVG Icon | m-slide-toggle |
| Material Select | m-icon-svg |
| Material Slide toggle | m-slider |
| Material Slider thumbLabel | m-slider-tickInterval |
| Material Slider tickInterval Auto | m-list |
| Material Slider tickInterval | m-slider-tickInterval-auto |
| Material Slider | m-slider-vertical |
| Material Tab Group | m-tab |
| Material Tab | m-tooltip |
| Material Table Column | m-grid-list |
| Material Table | m-table-column |
| Material Toolbar with multiple rows | m-icon-fontawesome |
| Material Tooltip position | m-tooltip-with-position |
| Material Tooltip with position | m-table |
| Material Tooltip | m-tooltip-position |
| Material Vertical Slider | m-slider-thumbLabel |
| Material toggle button | m-card |
| Material toolbar row | m-toolbar-multiRow |
| Material toolbar | m-toolbar-row |
| Percent pipe - Usage: number_expression &#x7c; percent[:digitInfo] | ng-pipe-decimal |
| Pipe template | ng-pipe-example |
| Property: [property]=\"expression\" | ng-binding-twoway |
| Property: [property]=\"expression\" | ng-event |
| Rectangular Material button w/ elevation. | m-button-icon |
| Rectangular Material button w/ no elevation. | m-button-raised |
| Resolve Guard Route | ng-route-guard-canload |
| Router active link | ng-router-outlet |
| Router link | ng-router-attribute |
| Router link | ng-router-linkActive |
| Router outlet element with name | ng-route-guard-canactivate |
| Router outlet element | ng-router-outlet-name |
| Router template | ng-router-appmodule |
| Routes to include in a feature module | ng-router-link |
| Routes to include in root module | ng-router-featuremodule |
| Short date pipe - Format: 09/15/1971 | ng-pipe-date-full |
| Slice pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] | ng-pipe-currency |
| Small circular button w/ elevation. | m-button-toggle |
| Switch template | ng-property |
| TODO | ng-test-component-async |
| TODO | ng-test-directive |
| TODO | ng-test-pipe |
| TODO | ng-test-service |
| Test a pipe | ng-if |
| The World's Original Angular Conference | ng-router |
| Two-way data binding with the NgModel | ng-interpolation |
| Uppercase pipe | ng-pipe-lowercase |
| Usage: Bind to the hidden property. | ng-hide |
| Usage: Bind to the hidden property. | ng-href |
| Usage: Bind to the href property. | ng-src |
| Usage: Bind to the src property. | ng-orderBy |
| Use component instead. | ng-show |
| Use ngFor instead. | ng-click |
| import module or component from path; | ng-http-get |
| ng-component | Component with template and style urls |
| ng-directive | Directive template |
| ng-directive-attribute | Attribute directive |
| ng-directive-css | CSS directive |
| ng-validator | Angular validator snippet |
| ngRx Actions class | ng-rx-module |
| ngRx Reducer | ng-rx-actions |
| ngRx Root Module | ng-rx-action |
| ngRx Single action | ng-test-component-synchronous |
| ngRx Util | ng-rx-reducer |
| pre obj pipe async pipe json | ng-fx-import |
| pre obj pipe json | ng-debug-async |
| v4: If else directive: *ngIf=\"expression; else\" | ng-if-then-else |
| v4: If then else directive: *ngIf=\"expression; then; else\" | ng-for |
| v4: Titlecase pipe | ng-pipe-date |


## Installation (Mac)

1. Launch VS Code 
2. Quick Open (⌘+P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


## Installation (Windows, Linux)

1. Launch VS Code 
2. Quick Open (Ctrl-Shift-P)
3. Enter the following command and press enter: 'ext install Angular-BeastCode'
4. Choose extension (Author: Mikael Morlund)
5. Reload VS Code 


## Feedback

Please send any feedback or suggestions to @Mike_BeastCode (Twitter) or create an issue on GitHub.

## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/labels/first-timers-only)


## Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data.


## License

MIT