<a name="0.8.1"></a>
## [0.8.1](https://github.com/SebastianM/angular2-google-maps/compare/0.8.0...v0.8.1) (2016-02-28)


### Bug Fixes

* **SebmGoogleMap:** allow styling via comp styles ([509b610](https://github.com/SebastianM/angular2-google-maps/commit/509b610)), closes [#162](https://github.com/SebastianM/angular2-google-maps/issues/162) [#169](https://github.com/SebastianM/angular2-google-maps/issues/169)
* **SebmGoogleMapMarker:** longitude changes ([e4ca50b](https://github.com/SebastianM/angular2-google-maps/commit/e4ca50b)), closes [#163](https://github.com/SebastianM/angular2-google-maps/issues/163) [#167](https://github.com/SebastianM/angular2-google-maps/issues/167)



<a name="0.8.0"></a>
# [0.8.0 clean-phantom](https://github.com/SebastianM/angular2-google-maps/compare/0.6.1...0.8.0) (2016-02-21)


### Bug Fixes

* **SebmGogleMapMarker:** label updates ([e2b9923](https://github.com/SebastianM/angular2-google-maps/commit/e2b9923))

### Features

* rename MapMouseEvent to MouseEvent ([978e881](https://github.com/SebastianM/angular2-google-maps/commit/978e881)), closes [#148](https://github.com/SebastianM/angular2-google-maps/issues/148)
* support angular beta.7 ([66ccfe7](https://github.com/SebastianM/angular2-google-maps/commit/66ccfe7)), closes [#144](https://github.com/SebastianM/angular2-google-maps/issues/144)
* **LazyMapsAPILoader:** support libraries query param ([a94662f](https://github.com/SebastianM/angular2-google-maps/commit/a94662f)), closes [#114](https://github.com/SebastianM/angular2-google-maps/issues/114)
* **LazyMapsAPILoader:** support region & language ([a127a79](https://github.com/SebastianM/angular2-google-maps/commit/a127a79)), closes [#102](https://github.com/SebastianM/angular2-google-maps/issues/102) [#125](https://github.com/SebastianM/angular2-google-maps/issues/125)
* **SebmGoogleMap:** support disableDefaultUI MapOption ([a5c9002](https://github.com/SebastianM/angular2-google-maps/commit/a5c9002)), closes [#103](https://github.com/SebastianM/angular2-google-maps/issues/103) [#113](https://github.com/SebastianM/angular2-google-maps/issues/113)
* **SebmGoogleMapMarker:** add draggable option ([a8ba736](https://github.com/SebastianM/angular2-google-maps/commit/a8ba736)), closes [#70](https://github.com/SebastianM/angular2-google-maps/issues/70) [#147](https://github.com/SebastianM/angular2-google-maps/issues/147)
* **SebmGoogleMapMarker:** support dragend event ([8f60c54](https://github.com/SebastianM/angular2-google-maps/commit/8f60c54)), closes [#71](https://github.com/SebastianM/angular2-google-maps/issues/71) [#149](https://github.com/SebastianM/angular2-google-maps/issues/149)


### BREAKING CHANGES

* `MapMouseEvent` is now called `MouseEvent`. Please update your
imports:

before:
```
import {MapMouseEvent} from 'angular2-google-maps/core';
```

after:
```
import {MouseEvent} from 'angular2-google-maps/core';
```


<a name="0.7.0"></a>
# [0.7.0](2016-02-21)
This release was incorrect; replaced with 0.8.0

<a name="0.6.1"></a>
## [0.6.1 shiny-neutron](https://github.com/SebastianM/angular2-google-maps/compare/0.6.0...0.6.1) (2016-01-30)


### Bug Fixes

* **SebmGoogleMap:** show map when zoom is not set ([b975c76](https://github.com/SebastianM/angular2-google-maps/commit/b975c76)), closes [#81](https://github.com/SebastianM/angular2-google-maps/issues/81)
* **SebmGoogleMapMarker:** run click event in zone ([2a3e390](https://github.com/SebastianM/angular2-google-maps/commit/2a3e390))
* **SebMGoogleMapMarker:** 0 value for lat/lng ([e65568e](https://github.com/SebastianM/angular2-google-maps/commit/e65568e)), closes [#82](https://github.com/SebastianM/angular2-google-maps/issues/82) [#101](https://github.com/SebastianM/angular2-google-maps/issues/101)

### Features

* **angular2:** support angular2-beta.2 ([592648c](https://github.com/SebastianM/angular2-google-maps/commit/592648c))



<a name="0.6.0"></a>
# [0.6.0 supersonic-scorpion](https://github.com/SebastianM/angular2-google-maps/compare/0.5.0...0.6.0) (2016-01-12)


### Bug Fixes

* **SebmGoogleMap:** use ngOnInit to support angular 2.0.0-beta.1 ([1c25cb9](https://github.com/SebastianM/angular2-google-maps/commit/1c25cb9)), closes [#79](https://github.com/SebastianM/angular2-google-maps/issues/79) [#76](https://github.com/SebastianM/angular2-google-maps/issues/76)

### Features

* **LazyMapsAPILoader:** make Google Maps API version configurable ([728960d](https://github.com/SebastianM/angular2-google-maps/commit/728960d))



<a name="0.5.0"></a>
# [0.5.0 eager-electron](https://github.com/SebastianM/angular2-google-maps/compare/0.4.0...0.5.0) (2015-12-27)


### Bug Fixes

* **package:** align peer & JSPM dependencies with ng2 beta.0 ([4fcd9af](https://github.com/SebastianM/angular2-google-maps/commit/4fcd9af))

### Features

* change file naming convention ([5a1ac76](https://github.com/SebastianM/angular2-google-maps/commit/5a1ac76))
* **packaging:** change package structure ([77d634e](https://github.com/SebastianM/angular2-google-maps/commit/77d634e))
* **SebmGoogleMap:**  support map click event ([c18640c](https://github.com/SebastianM/angular2-google-maps/commit/c18640c))
* **SebmGoogleMap:** support disableDoubleClickZoom mapOption ([fff0a29](https://github.com/SebastianM/angular2-google-maps/commit/fff0a29))
* **SebmGoogleMap:** support double-click event ([5f1ae68](https://github.com/SebastianM/angular2-google-maps/commit/5f1ae68))
* **SebmGoogleMap:** support right click event ([eab715e](https://github.com/SebastianM/angular2-google-maps/commit/eab715e))


### BREAKING CHANGES

* When you import a directive directly, you have to change the
import path:

Old:
```
import {SebmGoogleMap} from 'angular2-google-maps/directives/google_map';
```

New:
```
import {SebmGoogleMap} from 'angular2-google-maps/directives/google-map';
```

* The module name has changed. So you have to change your import path.  
  old: `angular2_google_maps/angular2_google_maps`  
  new: `angular2-google-maps/core`
* ES5 files that can be consumed using CommonJS are now in the root directory (old path was `/cjs/angular2_google_maps`)
* The ES6 files directory has changed:
  Old dir: `/es6/angular2_google_maps`  
  New dir: `/es6`
* The TypeScript files directory has changed:  
  Old dir: `/ts/angular2_google_maps`  
  New dir: `/ts`
* The `/typings` directory with bundled typings was deleted.  
  (Typings are now in the root directory seperated by file)



<a name="0.4.0"></a>
# [0.4.0](https://github.com/SebastianM/angular2-google-maps/compare/0.3.0...0.4.0) (2015-12-17)


### Features

* export ANGULAR2_GOOGLE_MAPS_DIRECTIVES ([83bcd9f](https://github.com/SebastianM/angular2-google-maps/commit/83bcd9f))
* **angular2:** support 2.0.0-beta.0 ([0bae421](https://github.com/SebastianM/angular2-google-maps/commit/0bae421)), closes [#51](https://github.com/SebastianM/angular2-google-maps/issues/51)
* **SebmGoogleMapMarker:** support click event ([2926de7](https://github.com/SebastianM/angular2-google-maps/commit/2926de7))


### BREAKING CHANGES

* angular2_google_maps/components module renamed
to angular2_google_maps/directives



<a name="0.3.0"></a>
# [0.3.0](https://github.com/SebastianM/angular2-google-maps/compare/0.2.0...0.3.0) (2015-12-10)


### Features

* **angular2:** add angular2.0.0-alpha.52 support ([8a1d813](https://github.com/SebastianM/angular2-google-maps/commit/8a1d813))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/SebastianM/angular2-google-maps/compare/0.1.0...0.2.0) (2015-11-19)


### Features

* **GoogleMapsAPILoading:** lazy load mechanism ([d05e6d3](https://github.com/SebastianM/angular2-google-maps/commit/d05e6d3))
* **sebmGoogleMapMarker:** support basic label ([f2e1257](https://github.com/SebastianM/angular2-google-maps/commit/f2e1257))


### BREAKING CHANGES

* GoogleMapsAPILoading:
  * You have to add the ANGULAR2_GOOGLE_MAPS_PROVIDERS to your `bootstrap()` method:
```typescript
import {ANGULAR2_GOOGLE_MAPS_PROVIDERS} from 'angular2_google_maps/angular2_google_maps';
bootstrap(myComponent, [ANGULAR2_GOOGLE_MAPS_PROVIDERS]);
```
  * Google Maps API v3 gets loaded automatically now by default. So you can remove the Google Maps API script tag from your page.
Alternatively, you can tell angular2-google-maps that the Google Maps API is already loaded on the page with this configuration:
```typescript
bootstrap(App, [
  ANGULAR2_GOOGLE_MAPS_PROVIDERS,
  // If you don't want to let angular2-google-maps load the Google Maps API script,
  // you can use the NoOpMapsAPILoader like this:
  provide(MapsAPILoader, {useClass: NoOpMapsAPILoader})
])
```



<a name="0.1.0"></a>
# 0.1.0 (2015-11-07)


### Features

* **components:** add sebm-google-map component ([120a5df](https://github.com/SebastianM/angular2-google-maps/commit/120a5df))
* **marker:** add basic marker support ([ec644a4](https://github.com/SebastianM/angular2-google-maps/commit/ec644a4))
