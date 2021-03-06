# CHANGES IN VERSION 0.1.5

## NEW FEATURES

- Modified: `signalCondition()`
    - Argument: `header`
          More fine control for headers
    - Argument: `time`
          Suppress timestamp in prefix
    - Argument: `pid`
          Suppress PID in prefix
    - Argument: `include_condition`
          Suppress condition in prefix
    - Unnamed message elements are not automatically treated as header anymore
- New: `newMessage()`
    Convenience wrapper around `signalCondition()` for `type = "message"`
- New: `newWarning()`
    Convenience wrapper around `signalCondition()` for `type = "warning"`
- New: `newError()`
    Convenience wrapper around `signalCondition()` for `type = "error"`
    
## BUG FIXES

## MAJOR CHANGES

- Modified: `signalCondition()`
    - Changed default condition classes to `DefaultMessage`, `DefaultWarning`, `DefaultError` and `DefaultCondition`
    
## MINOR CHANGES

## MISC

----------

# CHANGES IN VERSION 0.1.4

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

- Package now uses [packrat](http://cran.r-project.org/web/packages/packrat/index.html)
- Build for R-3.2.0

## MINOR CHANGES

- Removed: `rapp` directory
- Removed: `CHANGES.md` as `bumpr` is not ready yet
- Removed: `/inst/examples/refs`
- Renamed: `/tests/testthat/test-signalCondition-1.r` to `/tests/testthat/test-signalCondition.r`
- Modified: `/tests/testthat/test-signalCondition.r`

## MISC

-----

# CHANGES IN VERSION 0.1.3

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

## MISC

-----

# CHANGES IN conditionr VERSION 0.1.1.2

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

## MISC

- tried out interaction with `rapp.core.rte` (v0.1.0.2)

-----

# CHANGES IN conditionr VERSION 0.1.1.1

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

## MISC

- new patch version in order to comply repository conventions

-----

# CHANGES IN conditionr VERSION 0.1.1

Frozen: yes
Corresponds to patch version: `v0.1.0.3'

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

-----

# CHANGES IN conditionr VERSION 0.1.0.3

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES
