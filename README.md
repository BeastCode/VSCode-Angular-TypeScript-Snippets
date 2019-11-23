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
| ng-component | Component with template and style urls |
| ng-component-inline | Component with inline Template and Styles |
| ng-component-value-accessor | Angular Component With NG_VALUE_ACCESSOR |
| ng-directive | Directive template |
| ng-directive-attribute | Attribute directive |
| ng-directive-css | CSS directive |
| ng-validator | Angular validator snippet |


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