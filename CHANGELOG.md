# Changelog

## [Unreleased]

### New Features

### Enhancements

### Bug Fixes

## [0.6.0] - 2019-11-15

### New Features

- get charge state (return battery_level)
- set valet mode (true|false, password default:true,)
- reset valet pin
- speed limit activate (4DigitPIN default:4321)
- speed limit deactivate (4DigitPIN default:4321)
- speed limit set limit mph (50...90 default:50)
- speed limit clear pin (4DigitPIN default:4321)

### Enhancements

- set temps: boundary check for parameter
- Error message: flash reason if API call was not successful
  - set sentry mode
  - door unlock
  - door lock
  - actuate trunk
  - honk horn
  - flash lights
  - media toggle playback
  - media next track
  - media prev track
  - media next fav
  - media prev fav
  - media volume up
  - media volume down
  - set temps
  - auto conditioning start
  - auto conditioning stop
  - set preconditioning max
  - set remote seat heater request
  - set remote steering wheel heater request
  - set charge limit
  - set charge limit max range
  - set charge limit standard
  - charge port door open
  - charge port door close
  - charge start
  - charge stop
  - window control

### Bug Fixes

## [0.5.0] - 2019-11-05

### New Features

- set preconditioning max (true|false default:true)
- window control (close|vent default:close)

### Enhancements

- set sentry mode: check if parameter is either true or false, if not default is taken
- actuate trunk: check if parameter is either rear or front, if not default is taken
- deactivated some unnecessary text flash actions:
  - set remote seat heater request
  - set remote steering wheel heater request
  - set charge limit
  - set sentry mode
  - actuate trunk
  - set temps

### Bug Fixes

## [0.4.0] - 2019-11-03

### New Features

- auto conditioning start
- auto conditioning stop
- set remote seat heater request (heater=0..5,  level=0...3 default:0=driver,3=max)
- set remote steering wheel heater request (true|false default:true)
- set charge limit (0...100 default:80)
- set charge limit max range
- set charge limit standard
- charge port door open
- charge port door close
- charge start (untested)
- charge stop (untested)

### Enhancements

- new default value if no parameter given: set temps (driver temp, passenger temp default:20.5)
  
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

- Installations steps: first install dependencies added to be clear
  
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

## [.0.1.0] - 2019-09-21

- Initial release

[unreleased]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.6.0...HEAD
[0.6.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/v.0.1.0...v0.1.0
[.0.1.0]: https://github.com/JakobLichterfeld/Tesla_API_in_Tasker/compare/acb22ada4...v.0.1.0
