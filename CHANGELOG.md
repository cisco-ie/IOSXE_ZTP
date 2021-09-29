# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [V1.0]

### Added

-	Added persistent logging feature to save ZTP running-logs
-	Added a toggle switch to enable/disable persistent logging by flipping the flag ‘log_tofile = False’ in the script
-	Starting IOS XE 17.2.x and above the persistent log files will be saved under '/flash/guest-share/ztp.log' , In older version logs will be located at '/flash/ztp.log'
-	Skipped MD5 checksum on software versions where it is unsupported due to a known limitation(see Troubleshooting / Known Issues below)
-	Minor stability improvements 


### Changed

- None

### Fixed

- None

