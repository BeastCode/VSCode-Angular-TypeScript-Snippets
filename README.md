[![Version](https://vsmarketplacebadge.apphb.com/version/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

# VSCode Angular TypeScript & Html Snippets
Visual Studio Code TypeScript and Html snippets and code examples for Angular 2,4,5,6,7,8,9 & 10. 

All code snippets are based on and follow the Angular style guide https://angular.io/docs/ts/latest/guide/style-guide.html

The source for the snippets come from:
* https://angular.io/
* https://material.angular.io/
* https://github.com/angular/flex-layout
* https://github.com/ngrx/platform
* https://github.com/ngxs
* https://jestjs.io

and most of all, none of this would exist without the help of all the contributers for fixing, enhancing, testing and making suggestions.

# Snippet Prefixes

| Prefix | Description |
| ------- | ----------|
| ng- | Angular Snippets |
| fx- | Angular Flex Layout Snippets |
| ngrx- | Angular NgRx Snippets |
| ngxs- | Angular Ngxs Snippets |
| m- | Angular Material Design Snippets |
| rx- | RxJS Snippets for both TypeScript and JavaScript |
| sw- | Service Workers Snippets |
| t- | Test Snippets |
| e- | Test Expect Snippets |
| pwa- | Progressive Web Applications Snippets |

# Snippet Postfix

| Postfix | Description |
| ------- | ----------|
| -cheatsheet | Cheat Sheet |

# Important
This extension is optimized for developers that use Angular and are no longer using AngularJS (Angular 1).
If you type in AngularJS keywords, it will suggest an Angular solutions. 
This is by design and meant to help developers learn how AngularJS concepts and techniques map to Angular.

See example below for ng-repeat and ng-click:

![ngRepeatSnippet](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/raw/master/images/ngRepeatSnippet.gif)


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
All Material snippets starts with "m-" and there are now over 50 Material snippets in this package.

# Pro Tip

You don't need to type any dashes: "ngrxr" -> "ng-rx-reducer" snippet


### TypeScript & Html Snippets

| Snippet | Description |
| ------- | ----------|
|       "\"\": \"\", | ng-content |
| cli-cheatsheet | Cli Cheat Sheet |
| e-atbr | ExpectAsync toBeResolved |
| e-ntb | Expect Not toBe |
| e-ntbd | Expect not toBe Defined |
| e-ntbf | Expect not toBe Falsy |
| e-ntbn | Expect Not toBeNull |
| e-ntbt | Expect not toBe Truthy |
| e-ntbu | Expect not toBe Undefined |
| e-nthbc | Expect Not toHaveBeenCalled |
| e-ntm | Expect Not toMatch |
| e-ntmr | Expect Not toMatch regex |
| e-tb | Expect toBe |
| e-tbct | Expect toBeCloseTo |
| e-tbd | Expect toBe Defined |
| e-tbf | Expect toBe Falsy |
| e-tbgt | Expect toBeGreaterThan |
| e-tbgtoe | Expect toBeGreaterThanOrEqual |
| e-tbio | Expect toBeInstanceOf |
| e-tblt | Expect toBeLessThan |
| e-tbltoe | Expect toBeLessThanOrEqual |
| e-tbn | Expect toBeNull |
| e-tbt | Expect toBe Truthy |
| e-tbu | Expect toBe Undefined |
| e-tc | Expect toContain |
| e-thbc | Expect toHaveBeenCalled |
| e-thbcw | Expect toHaveBeenCalledWith |
| e-thlrw | Expect toHaveLastReturnedWith(value) |
| e-thnrw | Expect toHaveNthReturnedWith(nthCall, value) |
| e-thp | Expect toHaveProperty |
| e-thrt | Expect toHaveReturnedTimes(2) |
| e-thrw | Expect toHaveLastReturnedWith(value) |
| e-tm | Expect toMatch |
| e-tmo | Expect toMatchObject |
| e-tmr | Expect toMatch regex |
| e-tms | Jest Expect toMatchSnapshot |
| e-tse | Expect toStrictEqual |
| fx-col | Flex Layout Column |
| fx-col-element | Flex Layout Column with Element |
| fx-col-reverse | Flex Layout Reverse Column |
| fx-import | Flex Layout Import |
| fx-item | Flex Layout Item |
| fx-item-align | Flex Layout Item with fxFlexAlign |
| fx-item-fill | Flex Layout Item with fxFlexFill |
| fx-item-offset | Flex Layout Item with fxFlexOffset |
| fx-item-order | Flex Layout Item with fxFlexOrder |
| fx-layout | Flex Layout Property |
| fx-layout-align | Flex Layout Align Property |
| fx-layout-gap | Flex Layout Gap Property |
| fx-row | Flex Layout Row |
| fx-row-reverse | Flex Layout Reverse Row |
| m-accordion> | Material Accordion |
| m-button | Rectangular Material button w/ no elevation. |
| m-button-fab | Circular button w/ elevation. |
| m-button-fab-mini | Small circular button w/ elevation. |
| m-button-flat | Rectangular Material flat button. |
| m-button-icon | Circular Material button with a transparent background |
| m-button-raised | Rectangular Material button w/ elevation. |
| m-button-stroked | Rectangular Material button with a transparent background and a stroke. |
| m-button-toggle | Material toggle button |
| m-card | Material Basic Card |
| m-card-full | Material Card |
| m-checkbox | Material Checkbox |
| m-checkbox-ngmodel | Material Checkbox ngmodel |
| m-chip | Material Chip |
| m-chip-list | Material Chip List |
| m-chip-list-stacked | Material Chip Stacked List |
| m-datepicker | Material Datepicker |
| m-divider | Material Divider |
| m-divider-inset | Material Inset Divider |
| m-divider-vertical | Material Vertical Divider |
| m-drag-drop-box | Material drag drop box |
| m-expansion-panel | Material Expansion Panel |
| m-grid-list | Material Grid List |
| m-icon | Material Icon |
| m-icon-badge | Material Icon with a Badge |
| m-icon-fontawesome | Material Font Awesome Icon |
| m-icon-svg | Material SVG Icon |
| m-input | Material Input Textbox |
| m-list | Material List |
| m-list-item | Material List Item |
| m-list-ngfor | Material List ngFor |
| m-paginator | Material Paginator |
| m-progress-bar | Material Determinate Progress Bar |
| m-progress-bar-buffer | Material Buffer Progress Bar |
| m-progress-bar-indeterminate | Material indeterminate Progress Bar |
| m-progress-bar-query | Material Query Progress Bar |
| m-radiobutton | Material Radio Button |
| m-radiobutton-option | Material Radio Button Option |
| m-select | Material Select |
| m-slide-toggle | Material Slide toggle |
| m-slider | Material Slider |
| m-slider-thumbLabel | Material Slider thumbLabel |
| m-slider-tickInterval | Material Slider tickInterval |
| m-slider-tickInterval-auto | Material Slider tickInterval Auto |
| m-slider-vertical | Material Vertical Slider |
| m-spinner | Material Determinate Spinner |
| m-spinner-indeterminate | Material Indeterminate Spinner |
| m-step | Material Vertical Stepper |
| m-stepper-horizontal | Material Horizontal Stepper |
| m-stepper-vertical | Material Vertical Stepper |
| m-tab | Material Tab |
| m-tab-group | Material Tab Group |
| m-table | Material Table |
| m-table-column | Material Table Column |
| m-toolbar | Material toolbar |
| m-toolbar-multiRow | Material Toolbar with multiple rows |
| m-toolbar-row | Material toolbar row |
| m-tooltip | Material Tooltip |
| m-tooltip-position | Material Tooltip position |
| m-tooltip-with-position | Material Tooltip with position |
| nest-controller | Nest Controller |
| nest-dto | Nest Data Transfer Object with Swagger |
| nest-service | Nest Service |
| nest-swagger-main | Nest Add Swagger to main.ts |
| ng-afterContentChecked | Lifecycle hook: Called after every check of the component's or directive's content |
| ng-afterContentInit | Lifecycle hook: Called after ngOnInit when the component's or directive's content has been initialized |
| ng-afterViewChecked | Lifecycle hook: Called after every check of the component's view. Applies to components only |
| ng-afterViewInit | Lifecycle hook: Called after ngAfterContentInit when the component's view has been initialized |
| ng-binding-oneway | Property: [property]=\"expression\" |
| ng-binding-twoway | Two-way data binding with the NgModel |
| ng-bootstraping | Bootstraping example |
| ng-button | A button element with a click event |
| ng-button-submit | A submit button element with a click event |
| ng-class | CSS class |
| ng-click | Click event |
| ng-component | Component with template and style urls |
| ng-component-inline | Component with inline Template and Styles |
| ng-component-value-accessor | Angular Component With NG_VALUE_ACCESSOR |
| ng-conf | The World's Original Angular Conference |
| ng-container | Angular Container |
| ng-container-component | Angular Container with *ngContainerOutlet |
| ng-container-ngfor | Angular Container with *ngFor |
| ng-container-template | Angular Container with *ngTemplateOutlet |
| ng-controller | Use component instead. |
| ng-debug | pre obj pipe json |
| ng-debug-async | pre obj pipe async pipe json |
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
| ng-girls | Angular Girls |
| ng-hide | Usage: Bind to the hidden property. |
| ng-href | Usage: Bind to the href property. |
| ng-http-get | Http observable get request |
| ng-http-get-post | Http observable get & post request |
| ng-http-interceptor | Intercept an outgoing HttpRequest and optionally transform it or the response. |
| ng-httpClient-get | HttpClient observable get request |
| ng-if | If directive: *ngIf=\"expression\" |
| ng-if-else | v4: If else directive: *ngIf=\"expression; else\" |
| ng-if-then-else | v4: If then else directive: *ngIf=\"expression; then; else\" |
| ng-import | import module or component from path; |
| ng-input | Class Input Property |
| ng-interpolation | Interpolation: {{ interpolation }} |
| ng-material-module | App Material Module |
| ng-model | ngModel directive: [(ngModel)]=\"name\" |
| ng-module | Feature Module |
| ng-module-root | App root module |
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
| ng-pipe-titlecase | v4: Titlecase pipe |
| ng-pipe-uppercase | Uppercase pipe |
| ng-property | Property: [property]=\"expression\" |
| ng-repeat | Use ngFor instead. |
| ng-route-feature | Angular Route Feature |
| ng-route-guard-canactivate | CanActivate Guard Route |
| ng-route-guard-canactivatechild | CanActivateChild Route |
| ng-route-guard-candeactivate | CanDeactivate Guard Route |
| ng-route-guard-canload | CanLoad Guard Route |
| ng-route-guard-resolve | Resolve Guard Route |
| ng-route-lazy | Router link |
| ng-route-lazy-ivy | Router link |
| ng-router | Router template |
| ng-router-appmodule | Routes to include in root module |
| ng-router-attribute | Router link |
| ng-router-featuremodule | Routes to include in a feature module |
| ng-router-link | Router link |
| ng-router-linkActive | Router active link |
| ng-router-outlet | Router outlet element |
| ng-router-outlet-name | Router outlet element with name |
| ng-service | Basic service |
| ng-show | Usage: Bind to the hidden property. |
| ng-src | Usage: Bind to the src property. |
| ng-style | CSS style |
| ng-switch | Switch template |
| ng-template | Angular template |
| ng-validator | Angular validator snippet |
| ngrx-action-const | ngRx Single action |
| ngrx-action-creator | ngRx Single action with const |
| ngrx-action-creator-enum | ngRx Single action creator for enum |
| ngrx-actions | ngRx Actions class |
| ngrx-actiontype-enum | ngRx enum action type |
| ngrx-actiontypes-enum | ngRx enum action types |
| ngrx-effect | ngRx Effect |
| ngrx-module | ngRx Root Module |
| ngrx-reducer | ngRx Reducer |
| ngrx-util | ngRx Util |
| ngxs-action | Ngxs Action |
| ngxs-action-payload | Ngxs Action with Payload |
| ngxs-select | Ngxs Select |
| ngxs-state | Ngxs State |
| ngxs-state-model | Ngxs State Model |
| ngxs-store | Ngxs Store |
| ngxs-store-import | Ngxs Import Store |
| nx-cheatsheet | Nx Cheat Sheet |
| nx-ngrx-cheatsheet | Nx Cheat Sheet |
| pwa-link-manifest | PWA Link Manifest |
| pwa-manifest | PWA Json Manifest |
| rx-import-observable | RxJS Import Observable |
| rx-import-operator | RxJS Import an Operator |
| rx-import-subject | RxJS Import Subject |
| rx-mergeMap | RxJS MergeMap Example |
| sw-register | Register Service Worker |
| sw-register-and-check | Register Service Worker and Check |
| t-afterAll | afterAll |
| t-afterEach | afterEach |
| t-beforeAll | beforeAll |
| t-beforeEach | beforeEach |
| t-component-async | Test Async Component |
| t-component-sync | Test Synchronous Component |
| t-component-sync-old | Test Synchronous Component |
| t-describe | Describe |
| t-describe-it | Describe, It & Expect |
| t-directive | Test a directive |
| t-it | It |
| t-ite | It and Expect |
| t-module | Test Module |
| t-pipe | Test a pipe |
| t-service | Test a service |
| wat | A lightning talk by Gary Bernhardt from CodeMash 2012. ng-wat talk by Shai Reznik in 2015 |


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


## Emmets
If you want intellisense to show emmets before the snippets, you can force the emmets suggestions to show up at the top, by add the following to your editor user settings:

```javascript
{
  "emmet.showSuggestionsAsSnippets": true,
  "editor.snippetSuggestions": "top"
}
```


## Feedback

Please send any feedback or suggestions to @Mike_BeastCode (Twitter) or create an issue on GitHub.


## Open Source

This is an open source project and if you want to contribute I've added issues on github that are easy to start with. [![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/BeastCode/VSCode-Angular-TypeScript-Snippets/labels/first-timers-only)


## Disclaimer

Important: This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees or take any responsibility in case of lost data.


## License

MIT