## NexPlayer SDK for Unreal Release Notes

### Version 1.0.0
- [IOS]
	- [Added] Added support for IOS.
### Version 0.8.0
- [WebGL]
	- [Added] Added support for WebGL.

### Version 0.7.0
- [Android]
	- [Added] Added support for ID3 Timed Metadata.

### Version 0.6.0
- [Android]
	- [Added] Added support to control the playback autoplay.
	- [Added] Added support to mute the audio.
- [Windows]
	- [Added] Added support to control the playback autoplay.
	- [Added] Added support to mute the audio.

### Version 0.5.1
- [Unreal Engine]
	- [Added] Added support for Unreal Engine 5.0.0 Preview 2.

### Version 0.5.0
- [Unreal Engine]
	- [Added] Added support for Unreal Engine 5.0.0 Early Access 2.
- [Android]
	- [Added] Added support to control the playback looping.
- [Windows]
	- [Added] Added support to control the playback looping.

### Version 0.4.7
- [Windows]
	- [Fixed] Fixed a crash when the playback reaches the end of some video contents.

### Version 0.4.6
- [Unreal Engine]
	- [Added] Added license information for the sample.

### Version 0.4.5
- [Windows]
	- [Fixed] Prevented from using the player while the license is expired. Added a log when this happens.

### Version 0.4.4
- [Android]
	- [Fixed] Resolved an issue where certain live DASH video contents stuck buffering.

### Version 0.4.3
- [Android]
	- [Fixed] Apps packaged for distribution no longer crash while loading NexPlayer.

### Version 0.4.2
- [Android]
	- [Fixed] Removed the log of the current GMAxRHIShaderPlatform when using Unreal Engine 4.27 and above as it is no longer supported on non editor platforms

### Version 0.4.1.00
- [Fixed]
	- [macOS]
		- Ensured the plugin compiles properly even when the platform is not supported

### Version 0.4.0.00
- [Added]
	- [Android]
		- Added support for Oculus Quest

### Version 0.3.1.00
- [Fixed]
	- [Windows]
		- Fixed the player stopping immediately when playing a livestream
	- [Android]
		- Fixed the player status remaining blank while playing after end of content.

### Version 0.3.0.00
- [Added]
	- [Android]
		- Support for Android on Unreal Engine versions 4.22-4.26.
		- Support for Android OpenGL 2 and 3.1.
	- [All]
		- Player status and video content resolution UI.

### Version 0.2.1.00
- [Fixed]
	- [Windows]
		- Fixed a crash when stopping or pausing the video after 1 minute.
- [Changed]
	- [Windows]
		- Pause no longer toggles (resuming when paused).

### Version 0.2.0.00
- [Fixed]
	- [Windows]
		- The Unreal Engine editor play (viewport, standalone) no longer renders frames from previous executions.
		- Playing a video after stopping it no longer renders previous frames.
		- Playing a video after after if finishes no longer renders previous frames.
- [Changed]
	- [All]
		- Improved the project architecture.
- [Added]
	- [All]
		- Video Playback Event Delegates.
	- [Windows]
		- The video can be played again when the content ends.

### Version 0.1.2.00
- [Fixed]
	- [All]
		- Compilation errors when importing NexPlayerUnreal Plugin on custom projects with Unreal Engine versions 4.24 to 4.26.

### Version 0.1.1.00
- [Added]
	- [Windows]
		- Support for Windows packaged games.
- [Updated]
	- [All]
		- Replaced the default content url in the sample scenes.
	- [Windows]
		- Renamed NexPlayerPC to NexPlayerWindows.

### Version 0.1.0.00
- First beta version of NexPlayerUnreal, with basic functionality:
- [Added]
	- [Windows Editor, Android]
		- HLS and DASH content streaming with ABR (Adaptative Bitrate).
		- Rendering videos on 3D objects using material instances.
		- StartPlayer, Play, Pause, UpdatePlayer funcionalities.
