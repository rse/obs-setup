
OBS Setup
=========

Version 1.3.11 (2023-12-09)

This is [Dr. Ralf S. Engelschall](https://engelschall.com)'s opinionated
list of software components for installing a full-featured
[Open Broadcaster Software (OBS) Studio](https://obsproject.com/) setup
under Windows 10/11 (x64). For this, beside the base application, multiple
[OBS Studio Plugins](https://obsproject.com/forum/resources/categories/obs-studio-plugins.6/)
and companions scripts and tools should be installed. The intention of this
collection is to easily locate all the essential resources.

Notice: for the audio setup with VST plugins, see the [Audio Products](https://github.com/rse/audio-setup/blob/master/audio-products.md)
of my [companion Audio-Setup](https://github.com/rse/audio-setup)!

### Base Application

- **OBS Studio** 30.0.0 (GPL)<br/>
  Open Broadcaster Software (Video Mixing Application)<br/>
  [Homepage](https://obsproject.com/)
  [Download](https://github.com/obsproject/obs-studio/releases/download/30.0.0/OBS-Studio-30.0-Full-Installer-x64.exe)

### Essential Extensions

- **OBS WebSocket** 4.9.1-compat (GPL)<br/>
  Remote Control via OLD WebSockets (for StreamDeck, etc)<br/>
  [Homepage](https://github.com/Palakis/obs-websocket)
  [Download](https://github.com/obsproject/obs-websocket/releases/download/4.9.1-compat/obs-websocket-4.9.1-compat-Qt6-Windows-Installer.exe)

- **OBS NDI** 4.13.0/5.6.0.0 (GPL)<br/>
  Network Display Interface (NDI) input/output sources<br/>
  [Homepage](https://github.com/Palakis/obs-ndi)
  [Download](https://github.com/obs-ndi/obs-ndi/releases/download/4.13.0/obs-ndi-4.13.0-windows-x64-Installer.exe)
  [Download](https://downloads.ndi.tv/Tools/NDI%205%20Tools.exe)

### Plugins: Visual Effects

- **Composite Blur** 1.0.6 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-composite-blur)
  [Download](https://github.com/FiniteSingularity/obs-composite-blur/releases/download/v1.0.6/obs-composite-blur-1.0.6-windows-installer.zip)

- **Ahmanix Blur Filter** 1.0.1 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/ashmanix/blur-filter-obs-plugin)
  [Download](https://github.com/ashmanix/blur-filter-obs-plugin/releases/download/1.0.1/blur-filter-obs-plugin-1.0.1-windows-x64-Installer.exe)

- **Stroke Glow Shadow** 1.0.2 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-stroke-glow-shadow)
  [Download](https://github.com/FiniteSingularity/obs-stroke-glow-shadow/releases/download/v1.0.2/obs-stroke-glow-shadow-1.0.2-windows-installer.zip)

- **Background Removal** 1.1.7 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/occ-ai/obs-backgroundremoval)
  [Download](https://github.com/occ-ai/obs-backgroundremoval/releases/download/v1.1.7/obs-backgroundremoval-1.1.7-windows-x64-Installer.exe)

- **Virtual Background** 1.2.0 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/kounoike/obs-virtualbg)
  [Download](https://github.com/kounoike/obs-virtualbg/releases/download/v1.2.0/obs-virtualbg-v1.2.0-win64.zip)

- **Asynchronous Source Duplication** 0.4.1 (GPL)<br/>
  Asynchronous Source Duplication<br/>
  [Homepage](https://github.com/norihiro/obs-async-source-duplication)
  [Download](https://github.com/norihiro/obs-async-source-duplication/releases/download/0.4.1/obs-async-source-duplication-0.4.1-Windows-Installer.exe)

- **Shaderfilter** 2.1.3 (GPL)<br/>
  Shader Filter<br/>
  [Homepage](https://github.com/exeldro/obs-shaderfilter)
  [Download](https://github.com/exeldro/obs-shaderfilter/releases/download/2.1.1/obs-shaderfilter-2.1.3-windows-installer.exe)

- **Multi Source Effect** 0.2.1 (GPL)<br/>
  Combine to Sources with a Shader Effect<br/>
  [Homepage](https://github.com/norihiro/obs-multisource-effect)
  [Download](https://github.com/norihiro/obs-multisource-effect/releases/download/0.2.1/obs-multisource-effect-0.2.1-obs27-Windows.zip)

- **Face Tracker** 0.7.1 (GPL)<br/>
  AI-Based Face Tracking Effect<br/>
  [Homepage](https://github.com/norihiro/obs-face-tracker/)
  [Download](https://github.com/norihiro/obs-face-tracker/releases/download/0.7.1/obs-face-tracker-0.7.1-obs28-Windows.zip)

- **Gradient Source** 0.3.2 (GPL)<br/>
  Source for Rendered Gradient<br/>
  [Homepage](https://github.com/exeldro/obs-gradient-source)
  [Download](https://obsproject.com/forum/resources/gradient-source.1172/version/4964/download?file=95249)

- **Dynamic Delay** 0.1.4 (GPL)<br/>
  Dynamic Delay a Source<br/>
  [Homepage](https://github.com/exeldro/obs-dynamic-delay)
  [Download](https://obsproject.com/forum/resources/dynamic-delay.1035/version/4615/download?file=89293)

- **Time Warp Scan** 0.1.7 (GPL)<br/>
  Time Warp Scan Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-time-warp-scan)
  [Download](https://obsproject.com/forum/resources/time-warp-scan.1167/version/4604/download?file=89169)

- **Recursion Effect** 0.0.6 (GPL)<br/>
  Recurson Effect Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-recursion-effect)
  [Download](https://obsproject.com/forum/resources/recursion-effect.1008/version/5213/download?file=98828)

- **Freeze Filter** 0.3.3 (GPL)<br/>
  Frame Freeze Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-freeze-filter)
  [Download](https://obsproject.com/forum/resources/freeze-filter.950/version/4603/download?file=89160)

- **LiveVisionKit Filter** 1.2.2 (GPL)<br/>
  Video Effect Filters: Video Stabilizer, Adaptive De-Blocker, Lens Correction, Calibration Tool<br/>
  [Homepage](https://github.com/Crowsinc/LiveVisionKit)
  [Download](https://github.com/Crowsinc/LiveVisionKit/releases/download/v1.2.2/LiveVisionKit-1.2.2-Windows.zip)

- **Text Slideshow** 2.0.0 (GPL)<br/>
  Text Slideshow<br/>
  [Homepage](https://github.com/jbwong05/obs-text-slideshow)
  [Download](https://github.com/jbwong05/obs-text-slideshow/releases/download/v2.0.0-alpha/windows_libraries.zip)

- **URL/API Source** 0.2.5 (GPL)<br/>
  Fetch Live Data<br/>
  [Homepage](https://github.com/occ-ai/obs-urlsource)
  [Download](https://github.com/occ-ai/obs-urlsource/releases/download/0.2.5/obs-urlsource-0.2.5-windows-x64-Installer.exe)

- **Markdown Source** 0.2.2 (GPL)<br/>
  Render Markup Text<br/>
  [Homepage](https://github.com/exeldro/obs-markdown)
  [Download](https://obsproject.com/forum/resources/markdown-source.1764/version/5309/download?file=99932)

- **3D Effect** 0.1.0 (GPL)<br/>
  3D Effect Filter<br/>
  [Homepage](https://github.com/exeldro/obs-3d-effect)
  [Download](https://obsproject.com/forum/resources/3d-effect.1692/version/5316/download?file=99958)

- **9-Slice Filter** 1.0.0 (GPL)<br/>
  9-Slice Scaling Filter<br/>
  [Homepage](https://github.com/cmdwtf/filter-9slice)
  [Download](https://obsproject.com/forum/resources/9-slice-filter-plugin.1662/download)

- **Frame Interleave** 0.0.0 (GPL)<br/>
  Interleaves Video Frames to reduce CPU/GPU usage<br/>
  [Homepage](https://github.com/norihiro/obs-frame-interleave-filter/)
  [Download](https://github.com/norihiro/obs-frame-interleave-filter/releases/download/0.1.1/obs-frame-interleave-filter-0.1.1-obs27-Windows.zip)

- **FreeFX** 0.12.0b299 (GPL)<br/>
  Powerful Filters (Shaders, etc) and Source Mirror Source (StreamFX Clone)<br/>
  [Homepage](https://github.com/xoxfaby/obs-StreamFX)
  [Download](https://github.com/xoxfaby/obs-StreamFX/releases/download/0.12.0b299/streamfx-windows-installer.exe)

- **StreamFX** 0.11.1 (GPL)<br/>
  OBSOLETE: Powerful Filters (Shaders, etc) and Source Mirror Source<br/>
  [Homepage](https://github.com/Xaymar/obs-StreamFX)
  [Download](https://github.com/Xaymar/obs-StreamFX/releases/download/0.11.1/streamfx-windows-2019-0.11.1.0-g81a96998.exe)

### Plugins: Scene/Source Management

- **Scene Collection Manager** 0.0.8 (GPL)<br/>
  Filter/Backup/Restore Scene Collections<br/>
  [Homepage](https://github.com/exeldro/obs-scene-collection-manager)
  [Download](https://obsproject.com/forum/resources/scene-collection-manager.1434/version/4407/download?file=86112)

- **Source Clone** 0.1.4 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-clone)
  [Download](https://obsproject.com/forum/resources/source-clone.1632/version/4881/download?file=93639)

- **Source Copy** 0.2.2 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-copy)
  [Download](https://obsproject.com/forum/resources/source-copy.1261/version/4663/download?file=89992)

- **Replay Source** 1.6.12 (GPL)<br/>
  Instant Replay Sources from Memory<br/>
  [Homepage](https://github.com/exeldro/obs-replay-source)
  [Download](https://obsproject.com/forum/resources/replay-source.686/version/4903/download?file=94068)

- **Directory Watch Media** 0.6.2 (GPL)<br/>
  Filter you can add to Media Source to load the oldest/newest file in a directory<br/>
  [Homepage](https://github.com/exeldro/obs-dir-watch-media)
  [Download](https://obsproject.com/forum/resources/directory-watch-media.801/version/4826/download?file=92805)

- **Scene Tree Folder** 0.1.5 (GPL)<br/>
  Dock for Scene Tree View<br/>
  [Homepage](https://github.com/DigitOtter/obs_scene_tree_view/)
  [Download](https://github.com/DigitOtter/obs_scene_tree_view/releases/download/v0.1.5/obs_scene_tree_view_win_v0_1_5.zip)

- **xObsAsyncImageSource** 1.0 (GPL)<br/>
  Load Images Asynchronously<br/>
  [Homepage](https://github.com/YorVeX/xObsAsyncImageSource)
  [Download](https://github.com/YorVeX/xObsAsyncImageSource/releases/download/v1.0/xObsAsyncImageSource-win-x64.7z)

- **Source Defaults** 1.1.1 (GPL)<br/>
  Use Source for Defaults<br/>
  [Homepage](https://github.com/CodeYan01/source-defaults)
  [Download](https://github.com/CodeYan01/source-defaults/releases/download/v1.1.1/source-defaults-1.1.1-windows-x64-Installer.exe)

### Plugins: Scene/Source Control

- **Advanced Scene Switcher** 1.24.0 (GPL)<br/>
  Powerful Scene Switching<br/>
  [Homepage](https://obsproject.com/forum/resources/advanced-scene-switcher.395/)
  [Download](https://github.com/WarmUpTill/SceneSwitcher/releases/download/1.24.0/advanced-scene-switcher-windows-x64-Installer.exe)
  
- **Transition Table** 0.2.7 (GPL)<br/>
  Override Scene Transitions<br/>
  [Homepage](https://github.com/exeldro/obs-transition-table)
  [Download](https://obsproject.com/forum/resources/transition-table.1174/version/5172/download?file=98263)

- **Source Switcher** 0.4.2 (GPL)<br/>
  Source Switching between Multiple Sources<br/>
  [Homepage](https://github.com/exeldro/obs-source-switcher)
  [Download](https://obsproject.com/forum/resources/source-switcher.941/version/4963/download?file=95245)

- **Move Transition** 2.9.6 (GPL)<br/>
  Move Sources to New Position During Scene Transition<br/>
  [Homepage](https://github.com/exeldro/obs-move-transition)
  [Download](https://obsproject.com/forum/resources/move.913/version/5177/download?file=98341)

- **Media Controls** 0.3.6 (GPL)<br/>
  Control Dock for Media Playing<br/>
  [Homepage](https://github.com/exeldro/obs-media-controls)
  [Download](https://obsproject.com/forum/resources/media-controls.1032/version/4400/download?file=86062)

- **Vertical Canvas** 1.3.1 (GPL)<br/>
  Vertical Canvas for vertical video layouts<br/>
  [Homepage](https://github.com/Aitum/obs-vertical-canvas)
  [Download](https://github.com/Aitum/obs-vertical-canvas/releases/download/1.3.1/vertical-canvas-windows-installer.exe)

- **Scene as a Transition** 1.1.0 (GPL)<br/>
  Use a Scene as a Transition<br/>
  [Homepage](https://github.com/andilippi/obs-scene-as-transition)
  [Download](https://obsproject.com/forum/resources/scene-as-transition.1704/version/4852/download?file=93175)

- **Browser Transition** 0.1.2 (GPL)<br/>
  Use a Browser Source as a Transition<br/>
  [Homepage](https://github.com/exeldro/obs-browser-transition)
  [Download](https://obsproject.com/forum/resources/browser-transition.1653/version/5126/download?file=97629)

### Plugins: Streaming/Recording

- **Source Record** 0.3.2 (GPL)<br/>
  Individual Source Recording<br/>
  [Homepage](https://github.com/exeldro/obs-source-record)
  [Download](https://obsproject.com/forum/resources/source-record.1285/version/4683/download?file=90349)

- **Virtual Cam** 2.0.11 (GPL)<br/>
  Standalone Version of OBS Virtual Camera (supports 4 targets)<br/>
  [Homepage](https://github.com/miaulightouch/obs-virtual-cam)
  [Download](https://github.com/miaulightouch/obs-virtual-cam/releases/download/2.0.11/obs-virtualcam-2.0.11-windows-x64-Installer.exe)

- **Virtual Cam Filter** 0.0.6 (GPL)<br/>
  OBSOLETE: Export Source Video To (Virtual) Camera Device<br/>
  [Homepage](https://github.com/exeldro/obs-virtual-cam-filter)
  [Download](https://obsproject.com/forum/resources/virtual-cam-filter.1142/version/4086/download?file=81518)

- **Main View Source** 0.2.4 (GPL)<br/>
  Duplicate Main View<br/>
  [Homepage](https://github.com/norihiro/obs-main-view-source)
  [Download](https://github.com/norihiro/obs-main-view-source/releases/download/0.2.4/obs-main-view-source-0.2.4-obs27-Windows.zip)

- **Decklink Output Filter** 1.1.0 (GPL)<br/>
  Output Scenes/Sources to Blackmagic Decklink Cards<br/>
  [Homepage](https://github.com/cg2121/obs-decklink-output-filter)
  [Download](https://github.com/cg2121/obs-decklink-output-filter/releases/download/1.1.0/obs-decklink-output-filter-1.1.0-windows-x64-Installer.exe)

- **AJA Output Filter** 0.2.3 (GPL)<br/>
  Output Scenes/Sources to AJA Devices<br/>
  [Homepage](https://github.com/norihiro/obs-aja-output-filter)
  [Download](https://github.com/norihiro/obs-aja-output-filter/releases/download/0.2.3/obs-aja-output-filter-0.2.3-obs27-Windows.zip)

- **Audio Monitor** 0.8.3 (GPL)<br/>
  Export Source Audio To (Virtual) Speaker Device<br/>
  [Homepage](https://github.com/exeldro/obs-audio-monitor)
  [Download](https://obsproject.com/forum/resources/audio-monitor.1186/version/5063/download?file=96493)

- **Muted Notification** 1.0.1 (GPL)<br/>
  Play Sound when Parent Source is Muted<br/>
  [Homepage](https://git.vrsal.xyz/alex/urmuted)
  [Download](https://github.com/univrsal/urmuted/releases/download/v1.0.1/urmuted-1.0.1-windows-x64-Installer.exe)

- **VBAN Audio** 0.2.3 (GPL)<br/>
  Audio Source from and Outout VBAN (Audio over UDP) for VoiceMeeter<br/>
  [Homepage](https://github.com/norihiro/obs-vban/)
  [Download](https://github.com/norihiro/obs-vban/releases/download/0.2.3/obs-vban-0.2.3-obs27-Windows.zip)

- **Multi RTMP** 0.2.0.2 (GPL)<br/>
  Multiple RTMP Outputs<br/>
  [Homepage](https://github.com/sorayuki/obs-multi-rtmp)
  [Download](https://github.com/sorayuki/obs-multi-rtmp/releases/download/0.3.0.2-OBS29.1.1/obs-multi-rtmp-0.3.0.2-windows-x64-Installer.exe)

- **GStreamer** 0.4.0/1.20.3 (GPL)<br/>
  GStreamer Integration<br/>
  [Homepage](https://github.com/fzwoch/obs-gstreamer)
  [Download](https://github.com/fzwoch/obs-gstreamer/releases/download/v0.4.0/obs-gstreamer.zip)
  [Download](https://gstreamer.freedesktop.org/data/pkg/windows/1.22.3/mingw/gstreamer-1.0-mingw-x86_64-1.22.3.msi)

- **RTSP Server** 3.1.0 (GPL)<br/>
  Encode and publish RTSP/RTP Stream<br/>
  [Homepage](https://github.com/iamscottxu/obs-rtspserver)
  [Download](https://github.com/iamscottxu/obs-rtspserver/releases/download/v3.1.0-beta1/obs-rtspserver-v3.1.0-beta1-windows-installer.exe)

- **Teleport** 0.7.0 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/fzwoch/obs-teleport)
  [Download](https://github.com/fzwoch/obs-teleport/releases/download/0.7.0/obs-teleport.zip)

- **xObsBeam** 0.9.9 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/YorVeX/xObsBeam)
  [Download](https://github.com/YorVeX/xObsBeam/releases/download/v0.9.9-beta/xObsBeam-win-x64.7z)

- **Antavore** 0.0.1 (GPL)<br/>
  OBSOLETE: Audio Watermark Generator<br/>
  [Homepage](https://github.com/adam-sporka/antavore-obs)
  [Download](https://raw.githubusercontent.com/adam-sporka/antavore-obs/main/builds/2022-05-11/antavore.dll)

### Plugins: User Interface

- **Source Dock** 0.3.6 (GPL)<br/>
  Scene/Source as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-source-dock)
  [Download](https://obsproject.com/forum/resources/source-dock.1317/version/4888/download?file=93709)

- **Scene Notes Dock** 0.2.0 (GPL)<br/>
  Scene/Source Notes as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-scene-notes-dock)
  [Download](https://obsproject.com/forum/resources/scene-notes-dock.1398/version/5215/download?file=98836)

- **Downstream Keyer** 0.3.0 (GPL)<br/>
  Scene-Independent Overlay Sources<br/>
  [Homepage](https://github.com/exeldro/obs-downstream-keyer)
  [Download](https://obsproject.com/forum/resources/downstream-keyer.1254/version/5298/download?file=99767)

- **Durchblick** 0.5.0 (GPL)<br/>
  Alternative Multiview<br/>
  [Homepage](https://obsproject.com/forum/resources/durchblick.1484)
  [Download](https://obsproject.com/forum/resources/durchblick.1484/version/4186/download?file=83233)

- **Active Scene Dock** 0.1.2 (GPL)<br/>
  OBSOLETE: Show Preview/Program Duration<br/>
  [Homepage](https://github.com/layeh/obs-active-scene-dock)
  [Download](https://github.com/univrsal/durchblick/releases/download/v0.5.0/durchblick-0.5.0-windows-x64-Installer.exe)

### Plugins: Audio Input

- **ASIO** 3.1.1 (GPL)<br/>
  ASIO Audio Support<br/>
  [Homepage](https://github.com/Andersama/obs-asio)
  [Download](https://github.com/Andersama/obs-asio/releases/download/v3.1.1/obs-asio-3.1.1-windows-x64-Installer.exe)

### Plugins: Audio Monitoring

- **Color Monitor** 0.6.1 (GPL)<br/>
  Visualize Colors for Debugging Purposes<br/>
  [Homepage](https://github.com/norihiro/obs-color-monitor)
  [Download](https://github.com/norihiro/obs-color-monitor/releases/download/0.6.1/obs-color-monitor-0.6.1-obs28-Windows.zip)

- **Loudness Dock** 0.2.1 (GPL)<br/>
  Audio EBU R 128 Loudness Meter<br/>
  [Homepage](https://github.com/norihiro/obs-loudness-dock/)
  [Download](https://github.com/norihiro/obs-loudness-dock/releases/download/0.2.1/obs-loudness-dock-0.2.1-obs28-Windows.zip)

- **Waveform** 1.7.0 (GPL)<br/>
  Audio Waveform Visualization<br/>
  [Homepage](https://github.com/phandasm/waveform)
  [Download](https://github.com/phandasm/waveform/releases/download/v1.7.0/Waveform_v1.7.0_x86_64.zip)

- **Scale To Sound** 1.2.3 (GPL)<br/>
  OBSOLETE: Scale a Source to a Sound<br/>
  [Homepage](https://github.com/Qufyy/obs-scale-to-sound)
  [Download](https://github.com/dimtpap/obs-scale-to-sound/releases/download/1.2.3/obs-scale-to-sound-1.2.3-windows.zip)

- **Image Reaction** 1.2 (GPL)<br/>
  OBSOLETE: Switch Images to a Sound<br/>
  [Homepage](https://github.com/scaledteam/obs-image-reaction)
  [Download](https://github.com/scaledteam/obs-image-reaction/releases/download/1.2/obs-image-reaction-windows64.zip)

### Plugins: Audio Output

- **Asynchronous Audio Filter** 0.2.1 (GPL)<br/>
  Asynchronous Audio Filter<br/>
  [Homepage](https://github.com/norihiro/obs-async-audio-filter)
  [Download](https://github.com/norihiro/obs-async-audio-filter/releases/download/0.2.1/obs-async-audio-filter-0.2.1-obs27-Windows.zip)

- **Mute Filter** 0.2.2 (GPL)<br/>
  Mute Unwanted Audio<br/>
  [Homepage](https://github.com/norihiro/obs-mute-filter)
  [Download](https://github.com/norihiro/obs-mute-filter/releases/download/0.2.2/obs-mute-filter-0.2.2-obs27-Windows.zip)

- **Audio Pan Filter** 0.2.3 (GPL)<br/>
  Stereo Panning<br/>
  [Homepage](https://github.com/norihiro/obs-audio-pan-filter)
  [Download](https://github.com/norihiro/obs-audio-pan-filter/releases/download/0.2.3/obs-audio-pan-filter-0.2.3-obs27-Windows.zip)

- **CleanStream** 0.0.3 (GPL)<br/>
  Um-Removal<br/>
  [Homepage](https://github.com/occ-ai/obs-cleanstream)
  [Download](https://github.com/occ-ai/obs-cleanstream/releases/download/0.0.3/obs-cleanstream-0.0.3-windows-x64-Installer.exe)

- **LocalVocal** 0.0.7 (GPL)<br/>
  Local OpenAI Whisper Transcription<br/>
  [Homepage](https://github.com/occ-ai/obs-localvocal)
  [Download](https://github.com/occ-ai/obs-localvocal/releases/download/0.0.7/obs-localvocal-0.0.7-windows-x64-Installer.exe)

- **Polyglot** 0.0.1 (GPL)<br/>
  Local LLM Text Translation<br/>
  [Homepage](https://github.com/occ-ai/obs-polyglot)
  [Download](https://github.com/occ-ai/obs-polyglot/releases/download/0.0.1/obs-polyglot-0.0.1-windows-x64-Installer.exe)

- **BrAIn** 0.0.0 (GPL)<br/>
  Local LLM Engine<br/>
  [Homepage](https://github.com/occ-ai/obs-brAIn)
  [Download](https://github.com/occ-ai/obs-brAIn)

### Plugins: Meta-Information

- **Info Writer** 2.3 (GPL)<br/>
  Write Timestamps and Information Text to Logfiles<br/>
  [Homepage](https://github.com/partouf/OBSInfoWriter/)
  [Download](https://github.com/partouf/OBSInfoWriter/releases/download/v2.3/OBSInfoWriter-1.0.0-windows-x64-Installer.exe)

- **Chapter Marker** 1.0.3 (GPL)<br/>
  Write Timestamps to Video Recorded Files<br/>
  [Homepage](https://github.com/Davidj361/OBS-ChapterMarker)
  [Download](https://github.com/Davidj361/OBS-ChapterMarker/releases/download/1.0.3/ChapterMarker-win64.zip)

- **Local Stream Markers** 1.6 (GPL)<br/>
  Write Stream Markers to CSV File<br/>
  [Homepage](https://obsproject.com/forum/resources/local-stream-marker.1457/)
  [Download](https://obsproject.com/forum/resources/local-stream-marker.1457/download)

### Plugins: Media Import

- **Media Playlist Source** 0.0.5 (GPL)<br/>
  Media Playlist<br/>
  [Homepage](https://github.com/CodeYan01/media-playlist-source)
  [Download](https://github.com/CodeYan01/media-playlist-source/releases/download/0.0.5/media-playlist-source-0.0.5-windows-x64-Installer.exe)

- **Screenshot Filter** 1.5.2 (GPL)<br/>
  Source Screenshot Filter<br/>
  [Homepage](https://github.com/synap5e/obs-screenshot-plugin)
  [Download](https://github.com/synap5e/obs-screenshot-plugin/releases/download/1.5.2/obs-screenshot-filter-1.5.2-windows-x64.zip)

- **Ghostscript** 1.3 (GPL)<br/>
  OBSOLETE: PDF Rendering with Ghostscript<br/>
  [Homepage](https://github.com/nleseul/obs-ghostscript)
  [Download](https://github.com/nleseul/obs-ghostscript/releases/download/v1.3/obs-ghostscript-win.zip)

- **VNC Plugin** 0.4.0 (GPL)<br/>
  OBSOLETE: Display Remote Desktop via VNC<br/>
  [Homepage](https://github.com/norihiro/obs-vnc)
  [Download](https://github.com/norihiro/obs-vnc/releases/download/0.4.0/obs-vnc-0.4.0-Windows-Installer.exe)

- **Spout Plugin** 1.8 (GPL)<br/>
  Import/Export of Textures to and from SPOUT2 compatible programs<br/>
  [Homepage](https://github.com/Off-World-Live/obs-spout2-plugin)
  [Download](https://github.com/Off-World-Live/obs-spout2-plugin/releases/download/v1.8/OBS_Spout2_Plugin_Install_v1.8.exe)

- **Soundboard** 1.1.1 (GPL)<br/>
  Play Sound Files<br/>
  [Homepage](https://github.com/cg2121/obs-soundboard)
  [Download](https://github.com/cg2121/obs-soundboard/releases/download/1.1.1/obs-soundboard-1.1.0-windows-x64-Installer.exe)

- **Closed Captioning** 0.28 (GPL)<br/>
  Closed Captioning via Google Speech API<br/>
  [Homepage](https://github.com/ratwithacompiler/OBS-captions-plugin)
  [Download](https://github.com/ratwithacompiler/OBS-captions-plugin/releases/download/v0.28/Closed_Captions_Plugin__v0.28_Windows.zip)

- **OBS Lottie** 1.1.1 (GPL)<br/>
  Play Lottie Animation Files<br/>
  [Homepage](https://github.com/GrandMastersOnline/obs-lottie)
  [Download](https://github.com/GrandMastersOnline/obs-lottie/releases/download/v1.1.1/obs-lottie-1.1.1-windows-x64-Installer.exe)

- **DroidCam OBS Camera** 2.2.0 (GPL)<br/>
  Connect Mobile Phone (Android/iOS) as Camera to OBS Studio<br/>
  [Homepage](https://github.com/dev47apps/droidcam-obs-plugin)
  [Download](https://github.com/dev47apps/droidcam-obs-plugin/releases/download/2.2.0/DroidCamOBS.Setup.2.2.0.exe)

### Plugins: Remote Control

- **PTZControl** 0.15.4 (GPL)<br/>
  PTZ Camera Control<br/>
  [Homepage](https://github.com/glikely/obs-ptz)
  [Download](https://github.com/glikely/obs-ptz/releases/download/v0.15.4/obs-ptz-v0.15.4-windows-x64-Installer.exe)

- **Command Source** 0.4.0 (GPL)<br/>
  Dummy Source to Execute Commands when Scene Switched<br/>
  [Homepage](https://github.com/norihiro/obs-command-source)
  [Download](https://github.com/norihiro/obs-command-source/releases/download/0.4.0/obs-command-source-0.4.0-obs27-Windows.zip)

- **Input Overlay** 5.0.4 (GPL)<br/>
  Show Interactions<br/>
  [Homepage](https://github.com/univrsal/input-overlay)
  [Download](https://github.com/univrsal/input-overlay/releases/download/v5.0.4/input-overlay-5.0.4-windows-x64-Installer.exe)

### Remote Control Clients

- **OBS WebSocket JS** 5.0.3 (MIT)<br/>
  JavaScript Application Programming Interface (API) for OBS WebSockets API (for use from OBS docks)<br/>
  [Homepage](https://github.com/obs-websocket-community-projects/obs-websocket-js)
  [Download](https://unpkg.com/obs-websocket-js@5.0.3/dist/obs-websocket.min.js)

- **OBS WebSocket HTTP** 2 (GPL)<br/>
  Remote Control via HTTP (for OBS WebSocket)<br/>
  [Homepage](https://github.com/IRLToolkit/obs-websocket-http/)
  [Download](https://github.com/IRLToolkit/obs-websocket-http/releases/download/v2/obs-websocket-http-v2-Windows.exe)

- **OBS-Web** 5 (GPL)<br/>
  Remote Control via OBS WebSocket<br/>
  [Homepage](http://obs-web.niek.tv/)
  [Download](http://obs-web.niek.tv/)

- **OBS Simple HTTP Control** 1.1 (GPL)<br/>
  OBSOLETE: Remote Control via HTTP (for OBS WebSocket)<br/>
  [Homepage](https://obsproject.com/forum/resources/xobssimplehttpcontrol-simple-http-url-control-for-obs.1331/)
  [Download](https://obsproject.com/forum/resources/xobssimplehttpcontrol-simple-http-url-control-for-obs.1331/download)

- **OBS Command** 1.6.3 (FREEWARE)<br/>
  Command-Line Interface (CLI) for OBS WebSockets API<br/>
  [Homepage](https://github.com/REALDRAGNET/OBSCommand)
  [Download](https://github.com/REALDRAGNET/OBSCommand/releases/download/1.6.3/OBSCommand_1.6.3.zip)

- **TouchOSC** 1.2.3.178 (COMMERCIAL)<br/>
  Remote Control Deck<br/>
  [Homepage](https://hexler.net/touchosc)
  [Download](https://hexler.net/pub/touchosc/touchosc-1.2.3.178-win-x64.exe)

- **MATRIC** 2.6.23 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://matricapp.com/)
  [Download](https://matricapp.com/download/MatricSetup.2.6.23.exe)

- **NOOBS CMDR** 1.0.3 (FREEWARE)<br/>
  OBSOLETE: Macros for Scripting the OBS WebSockets API<br/>
  [Homepage](https://github.com/nuttylmao/NOOBS-CMDR)
  [Download](https://github.com/nuttylmao/NOOBS-CMDR/releases/download/V1.0.3/NOOBS.CMDR.V1.0.3.zip)

- **Touch Portal** 3.1.12 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://www.touch-portal.com)
  [Download](https://www.touch-portal.com/downloads/TouchPortal_Setup_release.exe)

- **Sammi (formerly LioranBoard)** 2.0 (OPEN SOURCE)<br/>
  Remote Control Deck for OBS Studio<br/>
  [Homepage](https://sammi.solutions/)
  [Download](https://sammi.solutions/docs/download)

- **Stream Deck** 6.3.0 (COMMERCIAL)<br/>
  Remote Control Deck for Android/iOS<br/>
  [Homepage](https://www.elgato.com/en/stream-deck)
  [Download](https://edge.elgato.com/egc/windows/sd/Stream_Deck_6.3.0.18948.msi)

- **Companion** 3.0.1 (OPEN SOURCE)<br/>
  Remote Control Deck for Elgato Streamdeck<br/>
  [Homepage](https://bitfocus.io/companion)
  [Download](https://bitfocus.io/companion)

- **MIDIControl** 2.0.5 (FREEWARE)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/Etuldan/MidiControl)
  [Download](https://github.com/Etuldan/MidiControl/releases/download/v2.0.5/MIDIControl_2.0.5_Setup.exe)

- **OBS-MIDI** 0.9.3a3.66 (GPL)<br/>
  OBSOLETE: Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/cpyarger/obs-midi)
  [Download](https://github.com/cpyarger/obs-midi/releases/download/tag-0.9.3-ALPHA-3.66/obs-midi-0.9.3-ALPHA-3.66-Windows-Installer.exe)

- **MIDI MG** 3.0.0 (GPL)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/nhielost/obs-midi-mg)
  [Download](https://github.com/nhielost/obs-midi-mg/releases/download/3.0.0-beta/obs-midi-mg-3.0.0-windows-x64-Installer.exe)

- **OSC for OBS** 3.1.3 (FREEWARE)<br/>
  Remote Control OBS via OSC<br/>
  [Homepage](https://github.com/jshea2/OSC-for-OBS)
  [Download](https://github.com/jshea2/OSC-for-OBS/releases/download/v3.0/OSC-for-OBS.3.1.3.-PC.zip)

- **CastMate** 0.4.9 (AGPL)<br/>
  Twitch/OBS Integration<br/>
  [Homepage](https://github.com/LordTocs/CastMate)
  [Download](https://github.com/LordTocs/CastMate/releases/download/v0.4.9/CastMate_0.4.9.exe)

### Themes

- **Ocean Blue** 0.1 (GPL)<br/>
  OBS Theme (Grey/Blue)<br/>
  [Homepage](https://obsproject.com/forum/resources/ocean-blue.1327/)
  [Download](https://github.com/Xaymar/obs-oceanblue/releases/download/0.1/OceanBlue-0.1.zip)

- **Flat Dark** 1.6.3 (GPL)<br/>
  OBS Theme (Grey)<br/>
  [Homepage](https://obsproject.com/forum/resources/flat-dark-theme.616/)
  [Download](https://obsproject.com/forum/resources/flat-dark-theme.616/download)

- **Cooliguay** 1.3 (GPL)<br/>
  OBS Theme (Grey/Purple)<br/>
  [Homepage](https://obsproject.com/forum/resources/cooliguay-theme.1405/)
  [Download](https://obsproject.com/forum/resources/cooliguay-theme.1405/download)

- **Streamlabs** 8.0.2 (GPL)<br/>
  OBS Theme (Grey/Cyan/Purple)<br/>
  [Homepage](https://obsproject.com/forum/resources/streamlabs-theme.887/)
  [Download](https://obsproject.com/forum/resources/streamlabs-theme.887/download)

### Browser Sources

- **RSE Crop Control** 1.0.0 (GPL)<br/>
  Remote Crop-Filter Control<br/>
  [Homepage](https://github.com/rse/obs-crop-control)
  [Download](https://github.com/rse/obs-crop-control/archive/refs/tags/1.0.0.tar.gz)

- **RSE Birddog Camera Preset** 1.0.0 (GPL)<br/>
  Recall Birddog Camera Preset<br/>
  [Homepage](https://github.com/rse/obs-birddog-camera-preset/)
  [Download](https://github.com/rse/obs-birddog-camera-preset/archive/refs/tags/1.0.0.tar.gz)

- **RSE Analog Clock** 1.6.2 (GPL)<br/>
  Nice Analog Clock<br/>
  [Homepage](https://github.com/rse/analogclock)
  [Download](https://github.com/rse/analogclock/archive/refs/tags/1.6.2.tar.gz)

- **RSE Lower Thirds** 0.9.5 (GPL)<br/>
  Automatically-Controlled Lower Thirds<br/>
  [Homepage](https://github.com/rse/lowerthird)
  [Download](https://github.com/rse/lowerthird/archive/refs/tags/0.9.5.tar.gz)

- **Lower Thirds with Dockable Control Panel** 1.6 (GPL)<br/>
  Semi-Manually-Controlled Lower Thirds<br/>
  [Homepage](https://obsproject.com/forum/resources/animated-lower-thirds-with-dockable-control-panel.1057/)
  [Download](https://obsproject.com/forum/resources/animated-lower-thirds-with-dockable-control-panel.1057/download)

- **WebRTC-Telestrator** 1.0.0 (GPL)<br/>
  Draw over Program<br/>
  [Homepage](https://github.com/BlankSourceCode/WebRTC-Telestrator)
  [Download](https://github.com/BlankSourceCode/WebRTC-Telestrator)

### Lua Scripts

- **RSE OBS Scripts** 2022-03 (GPL)<br/>
  Clone Template Scene, Keyboard Event Filter, Production Information, Refresh Browser Sources, Source One of Many<br/>
  [Homepage](https://github.com/rse/obs-scripts)
  [Download](https://github.com/rse/obs-scripts/archive/refs/heads/master.zip)

- **Advanced Timer** 6.0.0 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://github.com/cg2121/obs-advanced-timer/)
  [Download](https://github.com/cg2121/obs-advanced-timer/releases/download/6.0.0/advanced-timer.lua)

- **Countdown Adaptive Time** 2.1 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://obsproject.com/forum/resources/count-down-adaptive-time-with-auto-recording-scene-switcher.719/)
  [Download](https://obsproject.com/forum/resources/count-down-adaptive-time-with-auto-recording-scene-switcher.719/download)

- **Comprehensive Stopwatch & Countdown Timer** 5.5 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://obsproject.com/forum/resources/comprehensive-stopwatch-countdown-timer.1364/)
  [Download](https://github.com/midnight-studios/obs-lua/blob/main/StopWatch.lua)

- **Ashmanix Countdown Timer** 1.3.3 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://github.com/ashmanix/obs-plugin-countdown/)
  [Download](https://github.com/ashmanix/obs-plugin-countdown/releases/download/1.3.3/obs-plugin-countdown-1.3.3-windows-x64-Installer.exe)

- **Libre Macros** 3.3.0 (GPL)<br/>
  Attach Lua Console Scripts to Sources<br/>
  [Homepage](https://github.com/upgradeQ/obs-libre-macros)
  [Download](https://github.com/upgradeQ/obs-libre-macros/archive/refs/tags/3.3.0.zip)

- **Filter Hotkeys** 1.0.2 (MPL)<br/>
  Allow Hotkeys to Toggle Source Filters<br/>
  [Homepage](https://github.com/upgradeQ/obs-filter-hotkeys)
  [Download](https://github.com/upgradeQ/obs-filter-hotkeys/archive/refs/tags/1.0.2.tar.gz)

- **Color Curves** 1.2 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/color-curves.1540/)
  [Download](https://obsproject.com/forum/resources/color-curves.1540/download)

- **Clone Stamp** 1.2 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/clone-stamp.1535/)
  [Download](https://obsproject.com/forum/resources/clone-stamp.1535/download)

- **Corner Pin** 1.4 (GPL)<br/>
  Four Corner Pin Transform Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/corner-pin.1474/)
  [Download](https://obsproject.com/forum/resources/corner-pin.1474/download)

- **Lens Flare** 1.4 (GPL)<br/>
  Lens Flare Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/lens-flare-2.1495/)
  [Download](https://obsproject.com/forum/resources/lens-flare-2.1495/download)

- **Pan Zoom Rotate** 1.3 (GPL)<br/>
  Pan/Zoom/Rotate Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/pan-zoom-rotate.1489/)
  [Download](https://obsproject.com/forum/resources/pan-zoom-rotate.1489/download)

- **Color Correction** 1.1 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/3-axis-color-correction.1472/)
  [Download](https://obsproject.com/forum/resources/3-axis-color-correction.1472/download)

- **OBS Visca-over-IP Control** 2.2.1 (GPL)<br/>
  Control PTZ Cameras with VISCA-over-IP/UDP<br/>
  [Homepage](https://github.com/vwout/obs-visca-control)
  [Download](https://github.com/vwout/obs-visca-control/releases/download/2.2.1/obs-visca-control-2.2.1.zip)

- **Audio Status Monitor** 0.7 (GPL)<br/>
  Audio Status Monitoring Dock<br/>
  [Homepage](https://obsproject.com/forum/resources/audio-status-monitor.1381/)
  [Download](https://raw.githubusercontent.com/midnight-studios/obs-lua/main/SourceStatusMonitor.lua)

### Companion Audio Tools

- **OBS Audio Sync** 2019 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Video-Based)<br/>
  [Homepage](http://obsaudiosync.com/)
  [Download](https://share.hsforms.com/1GRBSRUxoTSCz56pblQR-WA8z4i)

- **LoistoSYNC** 2021-05 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Browser-Source-Based)<br/>
  [Homepage](https://github.com/reaby/loistoSYNC)
  [Download](http://reaby.kapsi.fi/dev/loistosync/)

- **Voice Attack** 1.8.9 (FREEWARE)<br/>
  Voice Control Commands<br/>
  [Homepage](https://voiceattack.com/)
  [Download](https://voiceattack.com/FileSend.aspx?id=VoiceAttackInstaller64.exe)

- **Virtual Audio Cable (VAC)** 4.70 (COMMERCIAL)<br/>
  Virtual Audio Cable<br/>
  [Homepage](https://vac.muzychenko.net/en/)
  [Download](https://software.muzychenko.net/trials/vac470.exe)

- **VoiceMeeter Potato** 3.0.2.8 (COMMERCIAL)<br/>
  Audio Channel Mixer, Virtual Audio Cable<br/>
  [Homepage](https://vb-audio.com/Voicemeeter/potato.htm)
  [Download](https://download.vb-audio.com/Download_CABLE/Voicemeeter8Setup.exe)

- **LoopMIDI** 1.0.16.27 (COMMERCIAL)<br/>
  Virtual MIDI Port<br/>
  [Homepage](https://www.tobias-erichsen.de/software/loopmidi.html)
  [Download](http://www.tobias-erichsen.de/wp-content/uploads/2020/01/loopMIDISetup_1_0_16_27.zip)

- **OcenAudio** 3.13.2 (FREEWARE)<br/>
  Digital Audio Workstation (with VST support)<br/>
  [Homepage](https://www.ocenaudio.com/)
  [Download](https://www.ocenaudio.com/start_download/ocenaudio64.exe)

- **Audacity** 3.4.1 (GPL)<br/>
  Audio Editor<br/>
  [Homepage](https://www.audacityteam.org/)
  [Download](https://github.com/audacity/audacity/releases/download/Audacity-3.4.1/audacity-win-3.4.1-x64.exe)

- **Cantabile** 4-4150 (FREEWARE)<br/>
  VST Host<br/>
  [Homepage](https://www.cantabilesoftware.com/)
  [Download](https://download.cantabilesoftware.com/SetupCantabile-4150.exe)

- **LightHost** 1.2.1 (GPL)<br/>
  VST Host<br/>
  [Homepage](https://github.com/rolandoislas/LightHost)
  [Download](https://github.com/rolandoislas/LightHost/releases/download/v1.2.1/Light.Host.1.2.1.Win64.zip)

- **Auto-Duck** 3.0.0-RC4.1 (COMMERCIAL)<br/>
  Audio-Ducking: Volume Reduction for Speaking over Audio<br/>
  [Homepage](https://auto-duck.com/)
  [Download](https://auto-duck.com/download-last)

### Companion Video Tools

- **Vingester** 2.8.0 (GPL)<br/>
  Web Contents Ingesting Tool (NDI-enabled)<br/>
  [Homepage](https://vingester.app/)
  [Download](https://github.oscdn.org/rse/vingester/2.8.0/Vingester-win-x64.zip)

- **Livemind Recorder** 0.9.4 (COMMERCIAL)<br/>
  NDI MultiViewer and Recorder<br/>
  [Homepage](https://livemind.tv/recorder/)
  [Download](https://dev.livemind.tv/download/?file=recorder/LivemindRecorder_v0.9.4.0.exe)

- **Lossless Cut** 3.58.0 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://github.com/mifi/lossless-cut/)
  [Download](https://github.com/mifi/lossless-cut/releases/download/v3.58.0/LosslessCut-win-x64.7z)

- **Shotcut** 23.11.29 (GPL)<br/>
  Video Editor<br/>
  [Homepage](https://shotcut.org/)
  [Download](https://github.com/mltframework/shotcut/releases/download/v23.11.29/shotcut-win64-231129.exe)

- **Blackmagicdesign DaVinci Resolve** 18.5 (COMMERCIAL, freely available)<br/>
  Video Editor<br/>
  [Homepage](https://www.blackmagicdesign.com/de/products/davinciresolve)
  [Download](https://www.blackmagicdesign.com/de/products/davinciresolve)

- **Kdenlive** 23.08.3 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://kdenlive.org/en/)
  [Download](https://download.kde.org/stable/kdenlive/23.08/windows/kdenlive-23.08.3.exe)

- **Handbrake** 1.7.1 (GPL)<br/>
  Video Converter<br/>
  [Homepage](https://handbrake.fr/)
  [Download](https://handbrake.fr/rotation.php?file=HandBrake-1.7.1-x86_64-Win_GUI.exe)

- **VLC** 3.0.20 (GPL)<br/>
  Video Player<br/>
  [Homepage](https://www.videolan.org/vlc/)
  [Download](https://get.videolan.org/vlc/3.0.20/win64/vlc-3.0.20-win64.exe)

- **CamooZ** 7.4.1 (FREEWARE)<br/>
  Camera Settings Management<br/>
  [Homepage](https://obsproject.com/forum/resources/camooz-manage-save-restore-camera-settings-local-and-remote.1271/)
  [Download](https://www.camooz.de/downloads/CamooZ.7.4.1.zip)

- **CamRename** 0.3 (FREEWARE)<br/>
  Camera Device Renaming<br/>
  [Homepage](https://obsproject.com/forum/resources/camrename.1408/)
  [Download](https://www.camooz.de/downloads/CamRename.0.3.zip)

- **OBS Graphic Clock** 3.5 (FREEWARE)<br/>
  Graphical Clock (Window-Captured)<br/>
  [Homepage](https://obsproject.com/forum/resources/obsgraphicclock-skinnable-analog-watch-with-countdown.1373/)
  [Download](https://obsproject.com/forum/resources/obsgraphicclock-skinnable-analog-watch-with-countdown.1373/download)

