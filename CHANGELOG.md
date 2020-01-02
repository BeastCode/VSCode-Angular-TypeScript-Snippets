# Angular BeastCode Changelog

## 8.1.0
 * Updates to support VS Code 1.40

## 8.0.0
 * Routing
   * ng-route
   * ng-route-lazy
   * ng-route-lazy-ivy
 * Snippets
   * ng-content
 * Tests
   * t-module
   * t-component-sync
  

## 7.2.0
 * Testing Snippets
   * ng-template
   * ng-container
   * ng-container-ngfor
   * ng-container-template
   * ng-container-component
 * Enhanced
   * t-pipe
   
## 7.0.0
 * Material
   * m-drag-drop-box
   * m-accordion

* Testing Expect To Snippets
   * e-thp (expect toHaveProperty)
   * e-tse (expect toStrictEqual)

 * Testing Snippets
   * t-directive
   * t-service
   * t-describe
   
## 6.2.0
 * Testing Snippets
    * t-beforeEach
    * t-afterEach
    * t-beforeAll
    * t-afterAll

 * Testing Expect To Snippets
    * e-tb (expect toBe)
    * e-ntb (expect not toBe)
    * e-tm (expect toMatch)
    * e-ntm (expect not toMatch)
    * e-tmr (expect toMatch regex)
    * e-ntmr (expect not toMatch regex)
    * e-tbn (expect toBeNull)
    * e-ntbn (expect not toBeNull)
    * e-tbf (expect toBeFalsy)
    * e-ntbf (expect not toBeFalsy)
    * e-tbt (expect toBeTruthy)
    * e-ntbt (expect not toBeTruthy)
    * e-tbd (expect toBeDefined)
    * e-ntbd (expect not toBeDefined)
    * e-tbu (expect toBeUndefined)
    * e-ntbu (expect not toBeUndefined)
    * e-tbgt (expect toBeGreaterThan)
    * e-tblt (expect toBeLessThan)
    * e-tbgtoe (expect toBeGreaterThanOrEqual)
    * e-tbltoe (expect toBeLessThanOrEqual)
    * e-tbct (expect toBeCloseTo)
    * e-thbc (expect toHaveBeenCalled)
    * e-nthbc (expect not toHaveBeenCalled)
    * e-thbcw (expect toHaveBeenCalledWith)
    * e-atbr (expectAsync toBeResolved)
    * e-thtr (expect toHaveReturnedTimes)
    * e-thrw (expect toHaveReturnedWith)
    * e-thnrw (expect toHaveNthReturnedWith)
    * e-thlrw (expect toHaveLastReturnedWith)
    * e-tbio (expect toBeInstanceOf)
    * e-tmo (expect toMatchObject)
    * e-tc (expect toContain)

* Jest Testing
    * e-tms (expect toMatchSnapshot)

* Snippets
    * ng-model

## 6.1.0
 * RxJS 
    * Multiple updates
    * RxJS mergeMap example
 * Testing Snippets
    * t-describe-it
    * t-it
    * t-ite
    * t-component-synchronous
    * t-component-async
    * t-pipe

## 6.0.0
 * pwa-manifest
 * ng-girls
 * ngxs-store
 * ngxs-store-import
 * ngxs-state
 * ngxs-state-model
 * ngxs-select
 * ngxs-action
 * ngxs-action-payload
 * cli-cheatsheet
 * nx-cheatsheet
 * nx-ngrx-cheatsheet
 * ngrx-action-creator
 * ngrx-action-creator-enum

## 5.2.x
 * ng-http-interceptor
 * m-checkbox-ngmodel
 * m-icon
 * m-icon-badge
 * ngxs-
 * m-divider
 * m-divider-inset
 * m-divider-vertical
 * sw-register
 * sw-register-and-check
 * pwa-link-manifest

Temporary removed
 * nx-cheatsheet
 * cli-cheatsheet

## 5.1.x
 * NgRX
   * ngrx-effect
   * ngrx-actions
   * ngrx-action-const
   * ngrx-actiontypes-enum
   * ngrx-actiontype-enum
* Mateial Design 5.0 Released
   * Removed all depricated md snippets
   * New
      * m-progress-bar
      * m-progress-bar-indeterminate
      * m-progress-bar-query
      * m-progress-bar-buffer

## 5.0.x
 * Mateial Design
    43 Material Snippets been updated to use mat- instead of md- for Materal 2.0.0-beta.11 .
    All new material snippets starts with m- and the old once have md- but will eventually be deleted.

 * New Material Snippets:
   * m-step
   * m-stepper-horizontal
   * mat-input-container -> mat-form-field
   * Updated mat-button-fab-mini
   * m-card-full
   * ng-material-module

 * New RxJS Snippets:
    * rx-import-all
    * rx-import-observable
    * rx-add-operator
    * rx-add-observable

 * Flex Layout:
   * All ng-fx snippets been renamed to fx-
   * Added fx-col-div snippets

## 4.4.x
 * Angular
    * ng-component-value-accessor
 * Material
    * m-expansion-panel
    * m-stepper-vertical

## 4.3.x
 * Angular 4.3
    * ng-httpClient-get
* Angular Material
    * m-chip-list
    * m-chip-list-stacked
    * m-chip
    * m-slider-vertical
    * m-button-toggle
    * m-icon-fontawesome
    * enhanced ng-if-else
    * m-spinner
    * m-spinner-indeterminate
    * m-slider-thumbLabel
    * m-slider-tickInterval-auto
    * m-slider-tickInterval

## 4.2.x

 * Router
    * ng-route-guard-canactivate
    * ng-route-guard-canactivatechild
    * ng-route-guard-candeactivate
    * ng-route-guard-canload
    * ng-route-guard-resolve
 * Angular Material
    * m-slide-toggle
    * m-slider
    * m-list
    * m-list-item
    * m-list-ngfor
    * m-tab
    * m-tab-group
    * m-tooltip
    * m-tooltip-position
    * m-tooltip-with-position
    * m-table
    * m-grid-list
    * m-paginator

## 4.1.x

 * Adding snippets for Angular Material. This is just experiental for now. Send me
   feedback if you think it belongs in the same package or not. 
   * m-button
   * m-button-fab
   * m-button-fab-mini
   * m-button-icon
   * m-button-raised
   * m-card
   * m-checkbox
   * m-datepicker
   * m-icon
   * m-icon-svg
   * m-input
   * m-select
   * m-toolbar
   * m-toolbar-multiRow
   * m-toolbar-row
   * m-radiobutton
   * m-radiobutton-option
 * Added Flex Layout Snippets
   * ng-fx-layout
   * ng-fx-layout-align
   * ng-fx-layout-gap

## 4.0.x

* Added Snippets for Angular v4
    * ng-if-else	
    * ng-if-then-else
    * ng-pipe-titlecase
* Added BeastCode Logo
* Added Router Snippets
    * ng-router-attribute
    * ng-router-appmodule
    * ng-router-featuremodule
* Improved Module Snippets
  * Updated ng-router-appmodule
* Eastereggs for ng-conf

## 2.4.x 

* Added Flex Layout Snippets
    * ng-fx-import
    * ng-fx-row
    * ng-fx-row-reverse
    * ng-fx-col	
    * ng-fx-col-reverse	
    * ng-fx-item	
    * ng-fx-item-align	
    * ng-fx-item-fill	
    * ng-fx-item-offset	
    * ng-fx-item-order
* Multiple Bug fixes
* Added ng-validator Snippet

## 0.3.x

* Adding Snippets
* Fixing Bugs

## 0.2.x 

* Initial Release to the Market 1/1/2017

## 0.1 

* Creating Snippets