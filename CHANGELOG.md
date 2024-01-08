# Changelog

## 0.1.0

### Added

- Haxe Module Manager support
- `no-deprecation-warnings` define

### Changed

- Updated libraries to the latest versions
- Moved PlayState song position update to before `super.update` call
- Changed SONG.song mentions to SONG.songName
- .gitignore, hxformat.json, and VS Code files modifications

### Removed

- Removed unused/unneeded files
- Removed `actuate` and `hxvm-luajit` libraries, as they're unused

### Fixed

- Fixed framerate issues
- Fixed song names being checked as incorrect lettercase
- Fixed vocals not resyncing when they're off-sync
- Fixed vocals replaying even after they're finished
- Fixed save not keeping sound settings
- Fixed underlay alpha in gameplay customize state
- Fixed strumline bounds in gameplay customize state
