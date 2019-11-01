# Changelog

## [Unreleased]

### New Features
- auto conditioning start
- auto conditioning stop
- set remote seat heater request (heater=0..5,  level=0...3 default:0=driver,3=max)

### Enhancements
- new Default value of no Parameter given: set temps (driver temp, passenger temp default:20.5)
  
### Bug Fixes

## [0.3.0] - 2019-10-10
### New Features
- media toggle playback
- media next track
- media prev track
- media next fav
- media prev fav
- media volume up
- media volume down
- set temps (driver temp, passenger temp default:21.0)
   
### Enhancements
- Installations steps: firs install dependencies added to be clear
  
### Bug Fixes
- set sentry mode (true|false default:true) now works as expected, activation and deactivation possible ([https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/issues/4](#4))
- actuate trunk (rear|front default:rear) now works as expected ([https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/issues/5](#5))
  
## [0.2.0] - 2019-10-09
### New Features
- set sentry mode (true|false default:true) - only false=deactivation working so far
- door unlock
- door lock
- actuate trunk (rear|front default:rear)
- honk horn
- flash lights
  
### Enhancements
- installation steps added
- overview of features as tasklist in readme.md
- use of id from get_vehicle ([https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/issues/2](#2))
- updated screenshots
  
### Bug Fixes
- use of id instead of vehicle_id

## [0.1.1] - 2019-09-23

### New Features
- Scene for initial Token get

### Enhancements
- Screenshots added

## [0.1.0] - 2019-09-21
- correct version naming
- 
## [.0.1.0] - 2019-09-21
- Initial release

[unreleased]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v.0.1.0...v0.1.0
[.0.1.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/acb22ada4...v.0.1.0
