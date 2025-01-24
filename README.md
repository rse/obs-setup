
OBS Setup
=========

Version 1.3.110 (2025-01-24)

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

- **OBS Studio** 31.0.1 (GPL)<br/>
  Open Broadcaster Software (Video Mixing Application)<br/>
  [Homepage](https://obsproject.com/)
  [Download](https://github.com/obsproject/obs-studio/releases/download/31.0.1/OBS-Studio-31.0.1-Full-Installer-x64.exe)

### Essential Extensions

- **DistroAV (formerly OBS NDI)** 6.0.0 (GPL)<br/>
  Network Display Interface (NDI) input/output sources<br/>
  [Homepage](https://github.com/DistroAV/DistroAV/)
  [Download](https://github.com/DistroAV/DistroAV/releases/download/6.0.0/distroav-6.0.0-windows-x64-Installer.exe)
  [Download](https://downloads.ndi.tv/Tools/NDI%206%20Tools.exe)

- **OBS WebSocket** 4.9.1-compat (GPL)<br/>
  OBSOLETE: Remote Control via OLD WebSockets (for StreamDeck, etc)<br/>
  [Homepage](https://github.com/Palakis/obs-websocket)
  [Download](https://github.com/obsproject/obs-websocket/releases/download/4.9.1-compat/obs-websocket-4.9.1-compat-Qt6-Windows-Installer.exe)

### Plugins: Visual Effects

- **Composite Blur** 1.1.0 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-composite-blur)
  [Download](https://github.com/FiniteSingularity/obs-composite-blur/releases/download/v1.1.0/obs-composite-blur-1.1.0-windows-installer.zip)

- **Ahmanix Blur Filter** 1.0.1 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/ashmanix/blur-filter-obs-plugin)
  [Download](https://github.com/ashmanix/blur-filter-obs-plugin/releases/download/1.0.1/blur-filter-obs-plugin-1.0.1-windows-x64-Installer.exe)

- **Stroke Glow Shadow** 1.0.2 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-stroke-glow-shadow)
  [Download](https://github.com/FiniteSingularity/obs-stroke-glow-shadow/releases/download/v1.0.2/obs-stroke-glow-shadow-1.0.2-windows-installer.zip)

- **Advanced Masks** 1.1.0 (GPL)<br/>
  Comprehensive Mask Filters<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-advanced-masks)
  [Download](https://github.com/FiniteSingularity/obs-advanced-masks/releases/download/v1.1.0/obs-advanced-masks-1.1.0-windows-installer.zip)

- **Background Removal** 1.1.13 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/locaal-ai/obs-backgroundremoval)
  [Download](https://github.com/locaal-ai/obs-backgroundremoval/releases/download/v1.1.13/obs-backgroundremoval-1.1.13-windows-x64-Installer.exe)

- **Detect** 0.0.3 (GPL)<br/>
  AI-Based Object Detection (for Blurring and Zooming)<br/>
  [Homepage](https://github.com/locaal-ai/obs-detect)
  [Download](https://github.com/locaal-ai/obs-detect/releases/download/0.0.3/obs-detect-0.0.3-windows-x64-Installer.exe)

- **Virtual Background** 1.2.0 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/kounoike/obs-virtualbg)
  [Download](https://github.com/kounoike/obs-virtualbg/releases/download/v1.2.0/obs-virtualbg-v1.2.0-win64.zip)

- **Asynchronous Source Duplication** 0.4.1 (GPL)<br/>
  Asynchronous Source Duplication<br/>
  [Homepage](https://github.com/norihiro/obs-async-source-duplication)
  [Download](https://github.com/norihiro/obs-async-source-duplication/releases/download/0.4.1/obs-async-source-duplication-0.4.1-Windows-Installer.exe)

- **Shaderfilter** 2.4.1 (GPL)<br/>
  Shader Filter<br/>
  [Homepage](https://github.com/exeldro/obs-shaderfilter)
  [Download](https://github.com/exeldro/obs-shaderfilter/releases/download/2.4.1/obs-shaderfilter-2.4.1-windows-installer.exe)

- **Multi Source Effect** 0.2.1 (GPL)<br/>
  Combine two Sources with a Shader Effect<br/>
  [Homepage](https://github.com/norihiro/obs-multisource-effect)
  [Download](https://github.com/norihiro/obs-multisource-effect/releases/download/0.2.1/obs-multisource-effect-0.2.1-obs27-Windows.zip)

- **Face Tracker** 0.7.2 (GPL)<br/>
  AI-Based Face Tracking Effect<br/>
  [Homepage](https://github.com/norihiro/obs-face-tracker/)
  [Download](https://github.com/norihiro/obs-face-tracker/releases/download/0.7.2/obs-face-tracker-0.7.2-obs28-Windows.zip)

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

- **Recursion Effect** 0.1.0 (GPL)<br/>
  Recurson Effect Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-recursion-effect)
  [Download](https://obsproject.com/forum/resources/recursion-effect.1008/version/5390/download?file=100717)

- **Freeze Filter** 0.3.4 (GPL)<br/>
  Frame Freeze Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-freeze-filter)
  [Download](https://obsproject.com/forum/resources/freeze-filter.950/version/6048/download?file=110875)

- **LiveVisionKit Filter** 1.2.2 (GPL)<br/>
  Video Effect Filters: Video Stabilizer, Adaptive De-Blocker, Lens Correction, Calibration Tool<br/>
  [Homepage](https://github.com/Crowsinc/LiveVisionKit)
  [Download](https://github.com/Crowsinc/LiveVisionKit/releases/download/v1.2.2/LiveVisionKit-1.2.2-Windows.zip)

- **Text Slideshow** 2.0.0 (GPL)<br/>
  Text Slideshow<br/>
  [Homepage](https://github.com/jbwong05/obs-text-slideshow)
  [Download](https://github.com/jbwong05/obs-text-slideshow/releases/download/v2.0.0-alpha/windows_libraries.zip)

- **Text (GDI+) with Templates** 1.2.2 (GPL)<br/>
  Text with Mustache Template Variable Interpolation<br/>
  [Homepage](https://obsproject.com/forum/resources/text-gdi-with-templates.1878/)
  [Download](https://obsproject.com/forum/resources/text-gdi-with-templates.1878/)

- **Text (FreeType) with Templates** 1.0.0 (GPL)<br/>
  Text with Mustache Template Variable Interpolation<br/>
  [Homepage](https://github.com/marktheminer/text-freetype2-mustache)
  [Download](https://github.com/marktheminer/text-freetype2-mustache/releases/download/1.0.0/text-freetype2-mustache-1.0.0-windows-x64-Installer.exe)

- **URL/API Source** 0.3.7 (GPL)<br/>
  Fetch Live Data<br/>
  [Homepage](https://github.com/locaal-ai/obs-urlsource)
  [Download](https://github.com/locaal-ai/obs-urlsource/releases/download/0.3.7/obs-urlsource-0.3.7-windows-x64-Installer.exe)

- **Markdown Source** 0.2.7 (GPL)<br/>
  Render Markup Text<br/>
  [Homepage](https://github.com/exeldro/obs-markdown)
  [Download](https://obsproject.com/forum/resources/markdown-source.1764/version/5994/download?file=110030)

- **3D Effect** 0.1.3 (GPL)<br/>
  3D Effect Filter<br/>
  [Homepage](https://github.com/exeldro/obs-3d-effect)
  [Download](https://obsproject.com/forum/resources/3d-effect.1692/version/5996/download?file=110049)

- **9-Slice Filter** 2.0.0 (GPL)<br/>
  9-Slice Scaling Filter<br/>
  [Homepage](https://github.com/cmdwtf/filter-9slice)
  [Download](https://obsproject.com/forum/resources/9-slice-filter-plugin.1662/version/5985/download?file=109845)

- **Frame Interleave** 0.0.0 (GPL)<br/>
  Interleaves Video Frames for non-Program display to reduce CPU/GPU usage<br/>
  [Homepage](https://github.com/norihiro/obs-frame-interleave-filter/)
  [Download](https://github.com/norihiro/obs-frame-interleave-filter/releases/download/0.1.1/obs-frame-interleave-filter-0.1.1-obs27-Windows.zip)

- **OCR - Text Recognition** 0.0.8 (GPL)<br/>
  OCR Text Recognition with Tesseract<br/>
  [Homepage](https://github.com/locaal-ai/obs-ocr)
  [Download](https://github.com/locaal-ai/obs-ocr/releases/download/0.0.8/obs-ocr-0.0.8-windows-x64-Installer.exe)

- **Encoder Region of Interest Editor** 1.1.1 (GPL)<br/>
  Encoder Optimization Hint for Region of Interest<br/>
  [Homepage](https://github.com/derrod/obs-roi-ui)
  [Download](https://github.com/derrod/obs-roi-ui/releases/download/1.1.1/obs-roi-ui-1.1.1-windows-x64-Installer.exe)

- **RTX SuperResolution** 1.2 (GPL)<br/>
  NVIDIA RTX Super Resolution Upscaler<br/>
  [Homepage](https://github.com/Bemjo/OBS-RTX-SuperResolution/)
  [Download](https://github.com/Bemjo/OBS-RTX-SuperResolution/releases/download/v1.2/release.zip)

- **Retro Effects** 1.0.0 (GPL)<br/>
  Many Retro Shader Effects<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-retro-effects/)
  [Download](https://github.com/FiniteSingularity/obs-retro-effects/releases/download/1.0.0/obs-retro-effects-1.0.0-windows-installer.zip)

- **FreeFX** 0.12.0b299 (GPL)<br/>
  OBSOLETE: Powerful Filters (Shaders, etc) and Source Mirror Source (StreamFX Clone)<br/>
  [Homepage](https://github.com/xoxfaby/obs-StreamFX)
  [Download](https://github.com/xoxfaby/obs-StreamFX/releases/download/0.12.0b299/streamfx-windows-installer.exe)

- **StreamFX** 1.0.0b610 (GPL)<br/>
  OBSOLETE: Powerful Filters (Shaders, etc) and Source Mirror Source<br/>
  [Homepage](https://github.com/Vhonowslend/StreamFX-Public)
  [Download](https://github.com/Vhonowslend/StreamFX-Public)

- **Flip Clock** 1.0.0.1 (GPL)<br/>
  Flip Clock<br/>
  [Homepage](https://github.com/PeterCang/flip-clock/)
  [Download](https://github.com/PeterCang/flip-clock/releases/download/1.0.0.1/FlipClock-Plugin-Install-v1.0.0.1.exe)

### Plugins: Scene/Source Management

- **Scene Collection Manager** 0.1.2 (GPL)<br/>
  Filter/Backup/Restore Scene Collections<br/>
  [Homepage](https://github.com/exeldro/obs-scene-collection-manager)
  [Download](https://obsproject.com/forum/resources/scene-collection-manager.1434/version/5888/download?file=108688)

- **Source Clone** 0.1.5 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-clone)
  [Download](https://obsproject.com/forum/resources/source-clone.1632/version/5627/download?file=104019)

- **Source Copy** 0.2.5 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-copy)
  [Download](https://obsproject.com/forum/resources/source-copy.1261/version/5884/download?file=108597)

- **Replay Source** 1.8.1 (GPL)<br/>
  Instant Replay Sources from Memory<br/>
  [Homepage](https://github.com/exeldro/obs-replay-source)
  [Download](https://obsproject.com/forum/resources/replay-source.686/version/6038/download?file=110759)

- **Directory Watch Media** 0.7.0 (GPL)<br/>
  Filter you can add to Media Source to load the oldest/newest file in a directory<br/>
  [Homepage](https://github.com/exeldro/obs-dir-watch-media)
  [Download](https://obsproject.com/forum/resources/directory-watch-media.801/version/5399/download?file=100890)

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

- **jrDockie** 1.4 (GPL)<br/>
  Save/Load Dock Settings<br/>
  [Homepage](https://github.com/dcmouser/obsPlugins/tree/main/jr/jrdockie)
  [Download](https://obsproject.com/forum/resources/jrdockie-save-and-load-window-and-dock-layouts.1955/download)

- **Quick Access Utility (QAU)** 1.0.2 (GPL)<br/>
  Quick Source/Scene Access Dock<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-quick-access-utility)
  [Download](https://github.com/FiniteSingularity/obs-quick-access-utility/releases/download/1.0.2/obs-quick-access-utility-1.0.2-windows-x64-Installer.exe)

### Plugins: Scene/Source Control

- **Advanced Scene Switcher** 1.28.1 (GPL)<br/>
  Powerful Scene Switching<br/>
  [Homepage](https://obsproject.com/forum/resources/advanced-scene-switcher.395/)
  [Download](https://github.com/WarmUpTill/SceneSwitcher/releases/download/1.28.1/advanced-scene-switcher-windows-x64-Installer.exe)

- **Move (Transition)** 3.1.1 (GPL)<br/>
  Move Sources to New Position (During Scene Transition or for Face Tracking)<br/>
  [Homepage](https://github.com/exeldro/obs-move-transition)
  [Download](https://obsproject.com/forum/resources/move.913/version/5890/download?file=108718)

- **Scene as a Transition** 1.1.1 (GPL)<br/>
  Use a Scene as a Transition<br/>
  [Homepage](https://github.com/andilippi/obs-scene-as-transition)
  [Download](https://obsproject.com/forum/resources/scene-as-transition.1704/version/5695/download?file=104916)

- **Transition Table** 0.2.7 (GPL)<br/>
  Override Scene Transitions<br/>
  [Homepage](https://github.com/exeldro/obs-transition-table)
  [Download](https://obsproject.com/forum/resources/transition-table.1174/version/5172/download?file=98263)

- **Source Switcher** 0.4.3 (GPL)<br/>
  Source Switching between Multiple Sources<br/>
  [Homepage](https://github.com/exeldro/obs-source-switcher)
  [Download](https://obsproject.com/forum/resources/source-switcher.941/version/5932/download?file=109189)

- **Media Controls** 0.4.1 (GPL)<br/>
  Control Dock for Media Playing<br/>
  [Homepage](https://github.com/exeldro/obs-media-controls)
  [Download](https://obsproject.com/forum/resources/media-controls.1032/version/5940/download?file=109315)

- **Aitum Vertical** 1.5.1 (GPL)<br/>
  Vertical Canvas for vertical video layouts<br/>
  [Homepage](https://github.com/Aitum/obs-vertical-canvas)
  [Download](https://github.com/Aitum/obs-vertical-canvas/releases/download/1.4.10/vertical-canvas-windows-installer.exe)

- **Browser Transition** 0.1.3 (GPL)<br/>
  Use a Browser Source as a Transition<br/>
  [Homepage](https://github.com/exeldro/obs-browser-transition)
  [Download](https://github.com/Aitum/obs-vertical-canvas/releases/download/1.5.1/vertical-canvas-windows-installer.exe)

### Plugins: Streaming/Recording

- **Source Record** 0.4.4 (GPL)<br/>
  Individual Source Recording<br/>
  [Homepage](https://github.com/exeldro/obs-source-record)
  [Download](https://obsproject.com/forum/resources/source-record.1285/version/5977/download?file=109731)

- **Virtual Cam** 2.1.2 (GPL)<br/>
  Standalone Version of OBS Virtual Camera (supports 4 targets)<br/>
  [Homepage](https://github.com/miaulightouch/obs-virtual-cam)
  [Download](https://github.com/miaulightouch/obs-virtual-cam/releases/download/2.1.2/obs-virtualcam-2.1.2-windows-x64-Installer.exe)

- **Aitum Multistream** 1.0.6 (GPL)<br/>
  Multiple RTMP Outputs<br/>
  [Homepage](https://github.com/Aitum/obs-aitum-multistream)
  [Download](https://github.com/Aitum/obs-aitum-multistream/releases/download/1.0.6/aitum-multistream-windows-installer.exe)

- **Branch Output** 1.0.2 (GPL)<br/>
  Multiple RTMP/SRT Outputs as a Source Filter<br/>
  [Homepage](https://github.com/OPENSPHERE-Inc/branch-output)
  [Download](https://github.com/OPENSPHERE-Inc/branch-output/releases/download/1.0.2/osi-branch-output-1.0.2-windows-x64-Installer.exe)

- **Multi RTMP** 0.5.0.4 (GPL)<br/>
  Multiple RTMP Outputs<br/>
  [Homepage](https://github.com/sorayuki/obs-multi-rtmp)
  [Download](https://github.com/sorayuki/obs-multi-rtmp/releases/download/0.5.0.4-flatpak/obs-multi-rtmp-0.5.0.4-windows-x64-Installer.exe)

- **GStreamer** 0.4.1/1.24.3 (GPL)<br/>
  GStreamer Integration<br/>
  [Homepage](https://github.com/fzwoch/obs-gstreamer)
  [Download](https://github.com/fzwoch/obs-gstreamer/releases/download/v0.4.1/obs-gstreamer.zip)
  [Download](https://gstreamer.freedesktop.org/data/pkg/windows/1.24.6/mingw/gstreamer-1.0-mingw-x86_64-1.24.6.msi)

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

- **Audio Monitor** 0.9.0 (GPL)<br/>
  Export Source Audio To (Virtual) Speaker Device and Graphical Meter<br/>
  [Homepage](https://github.com/exeldro/obs-audio-monitor)
  [Download](https://obsproject.com/forum/resources/audio-monitor.1186/version/6017/download?file=110400)

- **Muted Notification** 1.0.2 (GPL)<br/>
  Play Sound when Parent Source is Muted<br/>
  [Homepage](https://git.vrsal.xyz/alex/urmuted)
  [Download](https://github.com/univrsal/urmuted/releases/download/v1.0.2/urmuted-1.0.2-windows-x64-Installer.exe)

- **VBAN Audio** 0.3.0 (GPL)<br/>
  Audio Source from and to VBAN (Audio over UDP) for VoiceMeeter<br/>
  [Homepage](https://github.com/norihiro/obs-vban/)
  [Download](https://github.com/norihiro/obs-vban/releases/download/0.3.0/obs-vban-0.3.0-obs27-Windows.zip)

- **RTSP Server** 3.1.0 (GPL)<br/>
  Encode and publish RTSP/RTP Stream<br/>
  [Homepage](https://github.com/iamscottxu/obs-rtspserver)
  [Download](https://github.com/iamscottxu/obs-rtspserver/releases/download/v3.1.0/obs-rtspserver-v3.1.0-windows-installer.exe)

- **Teleport** 0.7.3 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/fzwoch/obs-teleport)
  [Download](https://github.com/fzwoch/obs-teleport/releases/download/0.7.3/obs-teleport.zip)

- **xObsBeam** 1.1.0 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/YorVeX/xObsBeam)
  [Download](https://github.com/YorVeX/xObsBeam/releases/download/v1.1.0/xObsBeam-win-x64.7z)

- **Antavore** 0.0.1 (GPL)<br/>
  OBSOLETE: Audio Watermark Generator<br/>
  [Homepage](https://github.com/adam-sporka/antavore-obs)
  [Download](https://raw.githubusercontent.com/adam-sporka/antavore-obs/main/builds/2022-05-11/antavore.dll)

### Plugins: User Interface

- **Source Dock** 0.4.1 (GPL)<br/>
  Scene/Source as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-source-dock)
  [Download](https://obsproject.com/forum/resources/source-dock.1317/version/5981/download?file=109826)

- **Scene Notes Dock** 0.2.0 (GPL)<br/>
  Scene/Source Notes as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-scene-notes-dock)
  [Download](https://obsproject.com/forum/resources/scene-notes-dock.1398/version/5215/download?file=98836)

- **Downstream Keyer** 0.3.3 (GPL)<br/>
  Scene-Independent Overlay Sources<br/>
  [Homepage](https://github.com/exeldro/obs-downstream-keyer)
  [Download](https://obsproject.com/forum/resources/downstream-keyer.1254/version/5949/download?file=109370)

- **OBS LowerThirdSwitcher** 1.0.0 (GPL)<br/>
  Scene-Based Lower Third Control<br/>
  [Homepage](https://github.com/levi-hrb/obs-plugin-lowerthirdswitcher)
  [Download](https://github.com/levi-hrb/obs-plugin-lowerthirdswitcher)

- **Durchblick** 0.5.0 (GPL)<br/>
  Alternative Multiview<br/>
  [Homepage](https://obsproject.com/forum/resources/durchblick.1484)
  [Download](https://obsproject.com/forum/resources/durchblick.1484/version/4186/download?file=83233)

- **Active Scene Dock** 0.1.2 (GPL)<br/>
  OBSOLETE: Show Preview/Program Duration<br/>
  [Homepage](https://github.com/layeh/obs-active-scene-dock)
  [Download](https://github.com/univrsal/durchblick/releases/download/v0.5.0/durchblick-0.5.0-windows-x64-Installer.exe)

### Plugins: Audio Input

- **ASIO** 3.2.0 (GPL)<br/>
  ASIO Audio Support<br/>
  [Homepage](https://github.com/Andersama/obs-asio)
  [Download](https://github.com/Andersama/obs-asio/releases/download/v3.2.0/obs-asio-3.2.0-windows-x64-Installer.exe)

### Plugins: Audio Monitoring

- **Audio Video Sync Dock** 0.1.0 (GPL)<br/>
  Visualize Colors of Cameras for Debugging Purposes<br/>
  [Homepage](https://github.com/norihiro/obs-audio-video-sync-dock/)
  [Download](https://github.com/norihiro/obs-audio-video-sync-dock/releases/download/0.1.0/obs-audio-video-sync-dock-0.1.0-obs30-Windows.zip)

- **Color Monitor** 0.8.2 (GPL)<br/>
  Visualize Colors of Cameras for Debugging Purposes<br/>
  [Homepage](https://github.com/norihiro/obs-color-monitor)
  [Download](https://github.com/norihiro/obs-color-monitor/releases/download/0.8.2/obs-color-monitor-0.8.2-obs28-Windows.zip)

- **Loudness Dock** 0.2.2 (GPL)<br/>
  Audio EBU R 128 Loudness Meter<br/>
  [Homepage](https://github.com/norihiro/obs-loudness-dock/)
  [Download](https://github.com/norihiro/obs-loudness-dock/releases/download/0.2.2/obs-loudness-dock-0.2.2-obs28-Windows.zip)

- **Waveform** 1.8.0 (GPL)<br/>
  Audio Waveform Visualization<br/>
  [Homepage](https://github.com/phandasm/waveform)
  [Download](https://github.com/phandasm/waveform/releases/download/v1.8.0/Waveform_v1.8.0_x86_64.zip)

- **Scale To Sound** 1.2.4 (GPL)<br/>
  OBSOLETE: Scale a Source to a Sound<br/>
  [Homepage](https://github.com/Qufyy/obs-scale-to-sound)
  [Download](https://github.com/dimtpap/obs-scale-to-sound/releases/download/1.2.4/obs-scale-to-sound-1.2.4-windows.zip)

- **Image Reaction** 1.2 (GPL)<br/>
  OBSOLETE: Switch Images to a Sound<br/>
  [Homepage](https://github.com/scaledteam/obs-image-reaction)
  [Download](https://github.com/scaledteam/obs-image-reaction/releases/download/1.2/obs-image-reaction-windows64.zip)

### Plugins: Audio Output

- **Asynchronous Audio Filter** 0.3.0 (GPL)<br/>
  Asynchronous Audio Filter<br/>
  [Homepage](https://github.com/norihiro/obs-async-audio-filter)
  [Download](https://github.com/norihiro/obs-async-audio-filter/releases/download/0.3.0/obs-async-audio-filter-0.3.0-obs27-Windows.zip)

- **Mute Filter** 0.3.0 (GPL)<br/>
  Mute Unwanted Audio<br/>
  [Homepage](https://github.com/norihiro/obs-mute-filter)
  [Download](https://github.com/norihiro/obs-mute-filter/releases/download/0.3.0/obs-mute-filter-0.3.0-obs27-Windows.zip)

- **Audio Pan Filter** 0.2.3 (GPL)<br/>
  Stereo Panning<br/>
  [Homepage](https://github.com/norihiro/obs-audio-pan-filter)
  [Download](https://github.com/norihiro/obs-audio-pan-filter/releases/download/0.2.3/obs-audio-pan-filter-0.2.3-obs27-Windows.zip)

- **CleanStream** 0.1.3 (GPL)<br/>
  Um-Removal<br/>
  [Homepage](https://github.com/locaal-ai/obs-cleanstream)
  [Download](https://github.com/locaal-ai/obs-cleanstream/releases/download/0.1.3/obs-cleanstream-0.1.3-windows-x64-Installer.exe)

- **LocalVocal** 0.3.9 (GPL)<br/>
  Local OpenAI Whisper Transcription<br/>
  [Homepage](https://github.com/locaal-ai/obs-localvocal)
  [Download](https://github.com/locaal-ai/obs-localvocal/releases/download/0.3.9/obs-localvocal-0.3.9-windows-x64-cuda-Installer.exe)

- **CloudVocal** 0.0.1 (GPL)<br/>
  Cloud Transcription<br/>
  [Homepage](https://github.com/locaal-ai/cloudvocal)
  [Download](https://github.com/locaal-ai/cloudvocal/releases/download/0.0.1/cloudvocal-0.0.1-windows-x64-Installer.exe)

- **Squawk** 0.0.4 (GPL)<br/>
  Local Text-to-Speech Generation<br/>
  [Homepage](https://github.com/locaal-ai/obs-squawk)
  [Download](https://github.com/locaal-ai/obs-squawk/releases/download/0.0.4/obs-squawk-0.0.4-windows-x64-Installer.exe)

- **Polyglot** 0.0.2 (GPL)<br/>
  Local LLM Text Translation<br/>
  [Homepage](https://github.com/locaal-ai/obs-polyglot)
  [Download](https://github.com/locaal-ai/obs-polyglot/releases/download/0.0.2/obs-polyglot-0.0.2-windows-x64-Installer.exe)

- **BrAIn** 0.0.0 (GPL)<br/>
  Local LLM Engine<br/>
  [Homepage](https://github.com/locaal-ai/obs-brAIn)
  [Download](https://github.com/locaal-ai/obs-brAIn)

### Plugins: Meta-Information

- **Info Writer** 2.3 (GPL)<br/>
  Write Timestamps and Information Text to Logfiles<br/>
  [Homepage](https://github.com/partouf/OBSInfoWriter/)
  [Download](https://github.com/partouf/OBSInfoWriter/releases/download/v2.3/OBSInfoWriter-1.0.0-windows-x64-Installer.exe)

- **Chapter Marker** 1.0.3 (GPL)<br/>
  Write Timestamps to Video Recorded Files<br/>
  [Homepage](https://github.com/Davidj361/OBS-ChapterMarker)
  [Download](https://github.com/Davidj361/OBS-ChapterMarker/releases/download/1.0.3/ChapterMarker-win64.zip)

- **StreamUP Chapter Marker Manager** 1.1.0 (GPL)<br/>
  Write Timestamps to Video Recorded Files<br/>
  [Homepage](https://github.com/StreamUPTips/obs-chapter-marker-manager)
  [Download](https://github.com/StreamUPTips/obs-chapter-marker-manager/releases/download/v1.1.0/streamup-chapter-marker-manager-windows-installer-v1.1.0.zip)

- **Local Stream Markers** 1.10 (GPL)<br/>
  Write Stream Markers to CSV File<br/>
  [Homepage](https://obsproject.com/forum/resources/local-stream-marker.1457/)
  [Download](https://obsproject.com/forum/resources/local-stream-marker.1457/download)

### Plugins: Media Import

- **Media Playlist Source** 0.0.7 (GPL)<br/>
  Media Playlist<br/>
  [Homepage](https://github.com/CodeYan01/media-playlist-source)
  [Download](https://github.com/CodeYan01/media-playlist-source/releases/download/0.0.7/media-playlist-source-0.0.7-windows-x64-Installer.exe)

- **Screenshot Filter** 1.5.2 (GPL)<br/>
  Source Screenshot Filter<br/>
  [Homepage](https://github.com/synap5e/obs-screenshot-plugin)
  [Download](https://github.com/synap5e/obs-screenshot-plugin/releases/download/1.5.2/obs-screenshot-filter-1.5.2-windows-x64.zip)

- **Ghostscript** 1.3 (GPL)<br/>
  OBSOLETE: PDF Rendering with Ghostscript<br/>
  [Homepage](https://github.com/nleseul/obs-ghostscript)
  [Download](https://github.com/nleseul/obs-ghostscript/releases/download/v1.3/obs-ghostscript-win.zip)

- **VNC Source** 0.6.1 (GPL)<br/>
  OBSOLETE: Display Remote Desktop via VNC<br/>
  [Homepage](https://github.com/norihiro/obs-vnc)
  [Download](https://github.com/norihiro/obs-vnc/releases/download/0.6.1/obs-vnc-0.6.1-Windows-Installer.exe)

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

- **DroidCam OBS Camera** 2.3.3 (GPL)<br/>
  Connect Mobile Phone (Android/iOS) as Camera to OBS Studio<br/>
  [Homepage](https://github.com/dev47apps/droidcam-obs-plugin)
  [Download](https://github.com/dev47apps/droidcam-obs-plugin/releases/download/2.3.3/DroidCamOBS.Setup.2.3.3.exe)

### Plugins: Remote Control

- **PTZControl** 0.15.4 (GPL)<br/>
  PTZ Camera Control<br/>
  [Homepage](https://github.com/glikely/obs-ptz)
  [Download](https://github.com/glikely/obs-ptz/releases/download/v0.15.4/obs-ptz-v0.15.4-windows-x64-Installer.exe)

- **Command Source** 0.5.0 (GPL)<br/>
  Dummy Source to Execute Commands when Scene Switched<br/>
  [Homepage](https://github.com/norihiro/obs-command-source)
  [Download](https://github.com/norihiro/obs-command-source/releases/download/0.5.0/obs-command-source-0.5.0-obs27-Windows.zip)

- **Input Overlay** 5.0.5 (GPL)<br/>
  Show Interactions<br/>
  [Homepage](https://github.com/univrsal/input-overlay)
  [Download](https://github.com/univrsal/input-overlay/releases/download/v5.0.5/input-overlay-5.0.5-windows-x64-Installer.exe)

### Remote Control Clients

- **Stream Deck** 6.3.0 (COMMERCIAL)<br/>
  Remote Control Deck for Android/iOS<br/>
  [Homepage](https://www.elgato.com/en/stream-deck)
  [Download](https://edge.elgato.com/egc/windows/sd/Stream_Deck_6.3.0.18948.msi)

- **Companion** 3.3.1 (OPEN SOURCE)<br/>
  Remote Control Deck for Elgato Streamdeck<br/>
  [Homepage](https://bitfocus.io/companion)
  [Download](https://bitfocus.io/companion)

- **TouchOSC** 1.3.1.204 (COMMERCIAL)<br/>
  Remote Control Deck<br/>
  [Homepage](https://hexler.net/touchosc)
  [Download](https://hexler.net/pub/touchosc/touchosc-1.3.1.204-win-x64.exe)

- **Touch Portal** 3.1.12 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://www.touch-portal.com)
  [Download](https://www.touch-portal.com/downloads/TouchPortal_Setup_release.exe)

- **Streamer.bot** 0.2.3 (FREEWARE)<br/>
  Remote Control Deck for OBS Studio<br/>
  [Homepage](https://streamer.bot/)
  [Download](https://streamer.bot/)

- **Sammi (formerly LioranBoard)** 2.0 (OPEN SOURCE)<br/>
  Remote Control Deck for OBS Studio<br/>
  [Homepage](https://sammi.solutions/)
  [Download](https://sammi.solutions/docs/download)

- **OBS WebSocket JS** 5.0.5 (MIT)<br/>
  JavaScript Application Programming Interface (API) for OBS WebSockets API (for use from OBS docks)<br/>
  [Homepage](https://github.com/obs-websocket-community-projects/obs-websocket-js)
  [Download](https://unpkg.com/obs-websocket-js@5.0.5/dist/obs-websocket.min.js)

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

- **MATRIC** 2.6.23 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://matricapp.com/)
  [Download](https://matricapp.com/download/MatricSetup.2.6.23.exe)

- **NOOBS CMDR** 1.0.3 (FREEWARE)<br/>
  OBSOLETE: Macros for Scripting the OBS WebSockets API<br/>
  [Homepage](https://github.com/nuttylmao/NOOBS-CMDR)
  [Download](https://github.com/nuttylmao/NOOBS-CMDR/releases/download/V1.0.3/NOOBS.CMDR.V1.0.3.zip)

- **Deckboard** 3.0.1 (OPEN SOURCE)<br/>
  Remote Control Deck for OBS<br/>
  [Homepage](https://deckboard.app/)
  [Download](https://github.com/rivafarabi/deckboard/releases)

- **MIDIControl** 2.0.5 (FREEWARE)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/Etuldan/MidiControl)
  [Download](https://github.com/Etuldan/MidiControl/releases/download/v2.0.5/MIDIControl_2.0.5_Setup.exe)

- **CoyoteMIDI** 189 (FREEWARE)<br/>
  Convert MIDI Events into Keystrokes/Mpise Events<br/>
  [Homepage](https://coyotemidi.com/)
  [Download](https://coyotemidi.com/download)

- **OBS MIDI MG** 3.0.3 (GPL)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/nhielost/obs-midi-mg)
  [Download](https://github.com/nhielost/obs-midi-mg/releases/download/3.0.3/obs-midi-mg-3.0.3-windows-x64-Installer.exe)

- **OSC for OBS** 3.1.3 (FREEWARE)<br/>
  Remote Control OBS via OSC<br/>
  [Homepage](https://github.com/jshea2/OSC-for-OBS)
  [Download](https://github.com/jshea2/OSC-for-OBS/releases/download/v3.0/OSC-for-OBS.3.1.3.-PC.zip)

- **CastMate** 0.4.9 (AGPL)<br/>
  Twitch/OBS Integration<br/>
  [Homepage](https://github.com/LordTocs/CastMate)
  [Download](https://github.com/LordTocs/CastMate/releases/download/v0.4.9/CastMate_0.4.9.exe)

- **OBSwitcher** 0 (AGPL)<br/>
  OBS Remote Scene Switcher<br/>
  [Homepage](http://www.cvhvisuals.com/obswitcher.html)
  [Download](http://www.cvhvisuals.com/obswitcher.html)

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

- **IROS** 0.0.0 (GPL)<br/>
  Place Text and Images on Canvas<br/>
  [Homepage](https://obsproject.com/forum/resources/iros-flexible-and-remotly-controllable-stream-overlay.1863/)
  [Download](https://obsproject.com/forum/resources/iros-flexible-and-remotly-controllable-stream-overlay.1863/)

### Lua Scripts

- **Lobster** 0 (GPL)<br/>
  Simplified OBS Lua API<br/>
  [Homepage](https://obsproject.com/forum/resources/lobster-an-api-wrapper-to-simplify-writing-obs-scripts.1874/)
  [Download](https://obsproject.com/forum/resources/lobster-an-api-wrapper-to-simplify-writing-obs-scripts.1874/)

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

- **Comprehensive Stopwatch & Countdown Timer** 5.9 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://obsproject.com/forum/resources/comprehensive-stopwatch-countdown-timer.1364/)
  [Download](https://github.com/midnight-studios/obs-lua/blob/main/StopWatch.lua)

- **Ashmanix Countdown Timer** 2.0.3 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://github.com/ashmanix/obs-plugin-countdown/)
  [Download](https://github.com/ashmanix/obs-plugin-countdown/releases/download/2.0.3/obs-plugin-countdown-2.0.3-windows-x64-Installer.exe)

- **Libre Macros** 4.0.0 (GPL)<br/>
  Attach Lua Console Scripts to Sources<br/>
  [Homepage](https://github.com/upgradeQ/obs-libre-macros)
  [Download](https://github.com/upgradeQ/obs-libre-macros/archive/refs/tags/4.0.0.zip)

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

- **OBS Visca-over-IP Control** 2.6 (GPL)<br/>
  Control PTZ Cameras with VISCA-over-IP/UDP<br/>
  [Homepage](https://github.com/vwout/obs-visca-control)
  [Download](https://github.com/vwout/obs-visca-control/releases/download/2.6/obs-visca-control-2.6.zip)

- **Audio Status Monitor** 0.7 (GPL)<br/>
  Audio Status Monitoring Dock<br/>
  [Homepage](https://obsproject.com/forum/resources/audio-status-monitor.1381/)
  [Download](https://raw.githubusercontent.com/midnight-studios/obs-lua/main/SourceStatusMonitor.lua)

- **Dynamic Source Grid Organization** 1.1 (GPL)<br/>
  Layout Sources of Scene in a Grid<br/>
  [Homepage](https://obsproject.com/forum/resources/dynamic-source-grid-organizer.2057/)
  [Download](https://obsproject.com/forum/resources/dynamic-source-grid-organizer.2057/)

### Companion Audio Tools

- **Youlean Loudness Meter** 2.4.3 (FREEWARE)<br/>
  Audio Analyzer<br/>
  [Homepage](https://youlean.co/youlean-loudness-meter/)
  [Download](https://cdn.youlean.co/wp-content/uploads/2021/02/Youlean-Loudness-Meter-2-V2.4.3-Windows-2.zip)

- **OBS Audio Sync** 2019 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Video-Based)<br/>
  [Homepage](http://obsaudiosync.com/)
  [Download](https://share.hsforms.com/1GRBSRUxoTSCz56pblQR-WA8z4i)

- **LoistoSYNC** 2021-05 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Browser-Source-Based)<br/>
  [Homepage](https://github.com/reaby/loistoSYNC)
  [Download](http://reaby.kapsi.fi/dev/loistosync/)

- **Voice Attack** 1.14 (FREEWARE)<br/>
  Voice Control Commands<br/>
  [Homepage](https://voiceattack.com/)
  [Download](https://voiceattack.com/FileSend.aspx?id=VoiceAttackInstaller64.exe)

- **Virtual Audio Cable (VAC)** 4.70 (COMMERCIAL)<br/>
  Virtual Audio Cable<br/>
  [Homepage](https://vac.muzychenko.net/en/)
  [Download](https://software.muzychenko.net/trials/vac470.exe)

- **VoiceMeeter Potato** 3.1.1.3 (COMMERCIAL)<br/>
  Audio Channel Mixer, Virtual Audio Cable<br/>
  [Homepage](https://voicemeeter.com/)
  [Download](https://download.vb-audio.com/Download_CABLE/Voicemeeter8Setup_v3113.zip)

- **VB Audio Matrix** 1.0.1.0 (COMMERCIAL)<br/>
  Audio Router for ASIO/Windows/VAIO/VBAN devices<br/>
  [Homepage](https://vb-audio.com/Matrix/index.htm)
  [Download](https://download.vb-audio.com/Download_Mixer/VBAudioMatrix_Setup_v1010.zip)

- **LoopMIDI** 1.0.16.27 (COMMERCIAL)<br/>
  Virtual MIDI Port<br/>
  [Homepage](https://www.tobias-erichsen.de/software/loopmidi.html)
  [Download](http://www.tobias-erichsen.de/wp-content/uploads/2020/01/loopMIDISetup_1_0_16_27.zip)

- **OcenAudio** 3.14.3 (FREEWARE)<br/>
  Digital Audio Workstation (with VST support)<br/>
  [Homepage](https://www.ocenaudio.com/)
  [Download](https://www.ocenaudio.com/start_download/ocenaudio64.exe)

- **Audacity** 3.6.4 (GPL)<br/>
  Audio Editor<br/>
  [Homepage](https://www.audacityteam.org/)
  [Download](https://github.com/audacity/audacity/releases/download/Audacity-3.6.4/audacity-win-3.6.4-x64.exe)

- **Cantabile** 4-4206 (FREEWARE)<br/>
  VST Host<br/>
  [Homepage](https://www.cantabilesoftware.com/)
  [Download](https://download.cantabilesoftware.com/SetupCantabile-4206.exe)

- **LightHost** 1.2.1 (GPL)<br/>
  VST Host<br/>
  [Homepage](https://github.com/rolandoislas/LightHost)
  [Download](https://github.com/rolandoislas/LightHost/releases/download/v1.2.1/Light.Host.1.2.1.Win64.zip)

- **Auto-Duck** 3.0.0-RC4.1 (COMMERCIAL)<br/>
  Audio-Ducking: Volume Reduction for Speaking over Audio<br/>
  [Homepage](https://auto-duck.com/)
  [Download](https://auto-duck.com/download-last)

### Companion Video Tools

- **Lossless Cut** 3.62.0 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://github.com/mifi/lossless-cut/)
  [Download](https://github.com/mifi/lossless-cut/releases/download/v3.62.0/LosslessCut-win-x64.7z)

- **Shutter Encoder** 18.5 (FREEWARE)<br/>
  Audio/Video Cutter<br/>
  [Homepage](https://www.shutterencoder.com/)
  [Download](https://www.shutterencoder.com/)

- **Shotcut** 24.09.13 (GPL)<br/>
  Video Editor<br/>
  [Homepage](https://shotcut.org/)
  [Download](https://github.com/mltframework/shotcut/releases/download/v24.09.13/shotcut-win64-240913.exe)

- **Handbrake** 1.8.2 (GPL)<br/>
  Video Converter<br/>
  [Homepage](https://handbrake.fr/)
  [Download](https://handbrake.fr/rotation.php?file=HandBrake-1.8.2-x86_64-Win_GUI.exe)

- **VLC** 3.0.21 (GPL)<br/>
  Video Player<br/>
  [Homepage](https://www.videolan.org/vlc/)
  [Download](https://get.videolan.org/vlc/3.0.21/win64/vlc-3.0.21-win64.exe)

- **MediaInfo** 24.06 (GPL)<br/>
  Audio/Video Analyzer<br/>
  [Homepage](https://mediaarea.net/en/MediaInfo)
  [Download](https://mediaarea.net/download/binary/mediainfo-gui/24.06/MediaInfo_GUI_24.06_Windows.exe)

- **Blackmagicdesign DaVinci Resolve** 19.0.1 (COMMERCIAL, freely available)<br/>
  Video Editor<br/>
  [Homepage](https://www.blackmagicdesign.com/de/products/davinciresolve)
  [Download](https://www.blackmagicdesign.com/de/products/davinciresolve)

- **Kdenlive** 24.02.0 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://kdenlive.org/en/)
  [Download](https://download.kde.org/stable/kdenlive/24.02/windows/kdenlive-24.02.0.exe)

- **Vingester** 2.8.0 (GPL)<br/>
  Web Contents Ingesting Tool (NDI-enabled)<br/>
  [Homepage](https://vingester.app/)
  [Download](https://github.oscdn.org/rse/vingester/2.8.0/Vingester-win-x64.zip)

- **Livemind Recorder** 0.9.4 (COMMERCIAL)<br/>
  NDI MultiViewer and Recorder<br/>
  [Homepage](https://livemind.tv/recorder/)
  [Download](https://dev.livemind.tv/download/?file=recorder/LivemindRecorder_v0.9.4.0.exe)

- **CamooZ** 7.4.2 (FREEWARE)<br/>
  Camera Settings Management<br/>
  [Homepage](https://webcamtool.de/)
  [Download](https://www.camooz.de/downloads/CamooZ.7.4.2.zip)

- **CamRename** 0.3 (FREEWARE)<br/>
  Camera Device Renaming<br/>
  [Homepage](https://obsproject.com/forum/resources/camrename.1408/)
  [Download](https://www.camooz.de/downloads/CamRename.0.3.zip)

- **OBS Graphic Clock** 3.5 (FREEWARE)<br/>
  Graphical Clock (Window-Captured)<br/>
  [Homepage](https://obsproject.com/forum/resources/obsgraphicclock-skinnable-analog-watch-with-countdown.1373/)
  [Download](https://obsproject.com/forum/resources/obsgraphicclock-skinnable-analog-watch-with-countdown.1373/download)

- **VDO.Ninja** 0 (FREEWARE)<br/>
  Remote Guest Ingest<br/>
  [Homepage](https://vdo.ninja/)
  [Download](https://vdo.ninja/)

- **SRC-Link** 0.6.0 (FREEWARE)<br/>
  Remote Guest Ingest<br/>
  [Homepage](https://src-link.live/)
  [Download](https://src-link.live/)

