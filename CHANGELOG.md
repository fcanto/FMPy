# Changelog

## [0.1.2] - 2017-12-21

### Changed
- 'fmpy' command is now directly accessible from the command line
- SSP schema updated to Draft20171219

## [0.1.1] - 2017-12-11

### Added
- dependency information in setup.py
- platform check for parameter variation example

### Fixed
- FMI call logging
- plot_result() now works with older matplotlib versions

### Changed
- timeout in cross-check removed

## [0.1.0] - 2017-11-24

### Added
- custom simulation loop and input example
- parameter variation example running on multiple cores
- experimental [System Structure and Parameterization](https://www.modelica.org/projects#ssp) support
- max. step size parameter for CVode solver

### Fixed
- return values in completedIntegratorStep()

## [0.0.9] - 2017-10-13

### Fixed
- set start values of type String

### Added
- CVode variable-step solver
- cross-check API for external tools

## [0.0.8] - 2017-09-10

### Fixed
- resourceLocation in FMU2.instantiate() now points to resources directory instead of unzip directory

### Added
- FMI functions (fmi1Reset, fmi2Reset, fmi2GetFMUState, fmi2SetFMUState, fmi2FreeFMUState)
