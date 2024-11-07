# sw-pw-web-core


## objectives

### Useful to CBG and PST (SW.com)

### Support for Functional and Visual testing
* Option to use multi-browser functional testing at the suite or test level (decorations?)
* Option to use Applitools grid for visual multi-browser & multi-viewport testing or local browser for mobile/browser specific logic
* Functional Options (single - forced single browser for everything, mixed - use one brower for erverything unless specified at test level, multiple - run all tests across all specified browsers)
* Visual Options (UFG - uses ENV specified or default browser to render dom and ships dom to UFG for code specified browser/device/viewport set, native - runs tests on specified brower set and does not use UFG. potentially useful for components with scripted device specific logic)
