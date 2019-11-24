[![Version](https://vsmarketplacebadge.apphb.com/version/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Mikael.Angular-BeastCode.svg)](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

# VSCode Angular TypeScript & Html Snippets
Visual Studio Code TypeScript and Html snippets and code examples for Angular 2,4,5,6, 7 & 8 Beta. 

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
|       "\t.setDescription('${}') | nest-controller |
| A button element with a click event | ng-import |
| A lightning talk by Gary Bernhardt from CodeMash 2012. ng-wat talk by Shai Reznik in 2015 | ng-conf |
| A submit button element with a click event | ng-button |
| Angular Component With NG_VALUE_ACCESSOR | ng-validator |
| Angular Container with *ngContainerOutlet | ng-template |
| Angular Container with *ngFor | ng-container-template |
| Angular Container with *ngTemplateOutlet | ng-container-component |
| Angular Container | ng-container-ngfor |
| Angular Girls | ng-router |
| Angular Route Feature | ng-route-lazy |
| Angular pipe example | ng-pipe-uppercase |
| Angular template | ngrx-util |
| Angular validator snippet | ng-directive |
| App Material Module | ng-pipe |
| App root module | ng-material-module |
| Async pipe - Usage: observable_or_promise_expression &#x7c; async | ng-ngOnChanges |
| Attribute directive | ng-service |
| Basic service | ng-bootstraping |
| Bootstraping example | ng-module |
| CSS class | ng-style |
| CSS directive | ng-directive-attribute |
| CSS style | ng-switch |
| CanActivate Guard Route | ng-route-guard-canactivatechild |
| CanActivateChild Route | ng-route-guard-resolve |
| CanDeactivate Guard Route | ng-container |
| CanLoad Guard Route | ng-route-guard-candeactivate |
| Circular Material button with a transparent background | m-button-fab |
| Circular button w/ elevation. | m-button-fab-mini |
| Class Input Property | ng-output |
| Class Output Event | ng-binding-oneway |
| Cli Cheat Sheet | pwa-manifest |
| Click event | ng-controller |
| Component with inline Template and Styles | ng-component-value-accessor |
| Component with template and style urls | ng-component-inline |
| Currency pipe - Usage: money &#x7c; currency:'EUR' | ng-pipe-json |
| Date pipe - Default format: 09/15/1971 | ng-pipe-date-custom |
| Date pipe - Format: \"MM/dd/yy\" = 09/15/71 | ng-pipe-date-short |
| Decimal pipe - Usage: number_expression &#x7c; decimal[:digitInfo] | ng-pipe-slice |
| Describe | t-describe-it |
| Describe, It & Expect | t-ite |
| Directive template | ng-directive-css |
| Event: (event) = \"onEvent()\" | ng-input |
| Expect Not toBe | e-tbf |
| Expect Not toBeNull | e-tbgt |
| Expect Not toHaveBeenCalled | e-thrt |
| Expect Not toMatch regex | e-tmo |
| Expect Not toMatch | e-tmr |
| Expect not toBe Defined | e-tbu |
| Expect not toBe Falsy | e-tbt |
| Expect not toBe Truthy | e-tbd |
| Expect not toBe Undefined | e-tm |
| Expect toBe Defined | e-ntbd |
| Expect toBe Falsy | e-ntbf |
| Expect toBe Truthy | e-ntbt |
| Expect toBe Undefined | e-ntbu |
| Expect toBe | e-ntb |
| Expect toBeCloseTo | e-thbc |
| Expect toBeGreaterThan | e-tbgtoe |
| Expect toBeGreaterThanOrEqual | e-tbltoe |
| Expect toBeInstanceOf | e-tbct |
| Expect toBeLessThan | e-tbio |
| Expect toBeLessThanOrEqual | e-tblt |
| Expect toBeNull | e-ntbn |
| Expect toContain | e-tbn |
| Expect toHaveBeenCalled | e-nthbc |
| Expect toHaveBeenCalledWith | e-thp |
| Expect toHaveLastReturnedWith(value) | e-thbcw |
| Expect toHaveLastReturnedWith(value) | e-thnrw |
| Expect toHaveNthReturnedWith(nthCall, value) | e-thlrw |
| Expect toHaveProperty | e-tse |
| Expect toHaveReturnedTimes(2) | e-thrw |
| Expect toMatch regex | e-ntmr |
| Expect toMatch | e-ntm |
| Expect toMatchObject | e-tc |
| Expect toStrictEqual | e-atbr |
| ExpectAsync toBeResolved | e-tms |
| Feature Module | ng-module-root |
| Flex Layout Align Property | fx-layout-gap |
| Flex Layout Column with Element | fx-col-reverse |
| Flex Layout Column | fx-col-element |
| Flex Layout Gap Property | fx-row-reverse |
| Flex Layout Import | fx-row |
| Flex Layout Item with fxFlexAlign | fx-item-fill |
| Flex Layout Item with fxFlexFill | m-drag-drop-box |
| Flex Layout Item with fxFlexOffset | fx-item-order |
| Flex Layout Item with fxFlexOrder | fx-item-align |
| Flex Layout Item | fx-item-offset |
| Flex Layout Property | fx-layout-align |
| Flex Layout Reverse Column | fx-item |
| Flex Layout Reverse Row | fx-col |
| Flex Layout Row | fx-layout |
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
| Intercept an outgoing HttpRequest and optionally transform it or the response. | sw-register |
| Interpolation: {{ interpolation }} | ng-repeat |
| It and Expect | t-it |
| It | t-beforeEach |
| Jest Expect toMatchSnapshot | ng-http-interceptor |
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
| Material Accordion | m-stepper-vertical |
| Material Basic Card | m-card-full |
| Material Buffer Progress Bar | m-progress-bar |
| Material Card | m-radiobutton |
| Material Checkbox ngmodel | m-checkbox |
| Material Checkbox | m-datepicker |
| Material Chip List | m-chip-list-stacked |
| Material Chip Stacked List | m-chip |
| Material Chip | m-select |
| Material Datepicker | m-input |
| Material Determinate Progress Bar | m-expansion-panel |
| Material Determinate Spinner | m-progress-bar-indeterminate |
| Material Divider | m-divider-inset |
| Material Expansion Panel | m-accordion> |
| Material Font Awesome Icon | m-button |
| Material Grid List | m-paginator |
| Material Horizontal Stepper | m-step |
| Material Icon with a Badge | m-slide-toggle |
| Material Icon | m-icon-badge |
| Material Indeterminate Spinner | m-divider |
| Material Input Textbox | m-chip-list |
| Material Inset Divider | m-divider-vertical |
| Material List Item | m-tab-group |
| Material List ngFor | m-list-item |
| Material List | m-list-ngfor |
| Material Paginator | m-spinner |
| Material Query Progress Bar | m-progress-bar-buffer |
| Material Radio Button Option | m-checkbox-ngmodel |
| Material Radio Button | m-radiobutton-option |
| Material SVG Icon | m-icon |
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
| Material Vertical Divider | rx-import-observable |
| Material Vertical Slider | m-slider-thumbLabel |
| Material Vertical Stepper | m-spinner-indeterminate |
| Material Vertical Stepper | m-stepper-horizontal |
| Material drag drop box | m-toolbar |
| Material indeterminate Progress Bar | m-progress-bar-query |
| Material toggle button | m-card |
| Material toolbar row | m-toolbar-multiRow |
| Material toolbar | m-toolbar-row |
| Nest Controller | nest-service |
| Nest Service | ng-component |
| Ngxs Action with Payload | ngxs-state-model |
| Ngxs Action | ngxs-action-payload |
| Ngxs Import Store | ngxs-select |
| Ngxs Select | t-component-sync-old |
| Ngxs State Model | ngxs-store |
| Ngxs State | ngxs-action |
| Ngxs Store | ngxs-store-import |
| Nx Cheat Sheet | cli-cheatsheet |
| Nx Cheat Sheet | nx-ngrx-cheatsheet |
| PWA Json Manifest |       "\"\": \"\", |
| PWA Link Manifest | sw-register-and-check |
| Percent pipe - Usage: number_expression &#x7c; percent[:digitInfo] | ng-pipe-decimal |
| Pipe template | ng-pipe-example |
| Property: [property]=\"expression\" | ng-binding-twoway |
| Property: [property]=\"expression\" | ng-event |
| Rectangular Material button w/ elevation. | m-button-icon |
| Rectangular Material button w/ no elevation. | m-button-raised |
| Register Service Worker and Check | nx-cheatsheet |
| Register Service Worker | pwa-link-manifest |
| Resolve Guard Route | ng-route-guard-canload |
| Router active link | ng-router-outlet |
| Router link | ng-route-lazy-ivy |
| Router link | ng-router-attribute |
| Router link | ng-router-link |
| Router link | ng-router-linkActive |
| Router outlet element with name | ng-route-guard-canactivate |
| Router outlet element | ng-router-outlet-name |
| Router template | ng-router-appmodule |
| Routes to include in a feature module | ng-route-feature |
| Routes to include in root module | ng-router-featuremodule |
| RxJS Import Observable | rx-import-subject |
| RxJS Import Subject | rx-import-operator |
| RxJS Import an Operator | rx-mergeMap |
| RxJS MergeMap Example | t-describe |
| Short date pipe - Format: 09/15/1971 | ng-pipe-date-full |
| Slice pipe - Usage: array_or_string_expression &#x7c; slice:start[:end] | ng-pipe-currency |
| Small circular button w/ elevation. | m-button-toggle |
| Switch template | ng-property |
| Test Async Component | t-directive |
| Test Module | t-component-async |
| Test Synchronous Component | t-component-sync |
| Test Synchronous Component | t-module |
| Test a directive | t-service |
| Test a pipe | ng-model |
| Test a service | t-pipe |
| The World's Original Angular Conference | ng-girls |
| Two-way data binding with the NgModel | ng-interpolation |
| Uppercase pipe | ng-pipe-lowercase |
| Usage: Bind to the hidden property. | ng-hide |
| Usage: Bind to the hidden property. | ng-href |
| Usage: Bind to the href property. | ng-src |
| Usage: Bind to the src property. | ng-orderBy |
| Use component instead. | ng-show |
| Use ngFor instead. | ng-click |
| afterAll | e-tb |
| afterEach | t-beforeAll |
| beforeAll | t-afterAll |
| beforeEach | t-afterEach |
| import module or component from path; | ng-http-get |
| nest-dto | Nest Data Transfer Object with Swagger |
| nest-swagger-main | Nest Add Swagger to main.ts |
| ng-content | Angular content |
| ngModel directive: [(ngModel)]=\"name\" | ng-if |
| ngRx Actions class | ngrx-module |
| ngRx Effect | ngxs-state |
| ngRx Reducer | ngrx-actions |
| ngRx Root Module | ngrx-action-const |
| ngRx Single action creator for enum | ngrx-actiontypes-enum |
| ngRx Single action with const | ngrx-action-creator-enum |
| ngRx Single action | ngrx-action-creator |
| ngRx Util | ngrx-reducer |
| ngRx enum action type | ngrx-effect |
| ngRx enum action types | ngrx-actiontype-enum |
| pre obj pipe async pipe json | fx-import |
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