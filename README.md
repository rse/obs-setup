
OBS Setup
=========

Version 1.3.171 (2026-06-15)

This is [Dr. Ralf S. Engelschall](https://engelschall.com)'s opinionated
list of software components for installing a full-featured
[Open Broadcaster Software (OBS) Studio](https://obsproject.com/) setup
under Windows 10/11 (x64). For this, beside the base application, multiple
[OBS Studio Plugins](https://obsproject.com/forum/resources/categories/obs-studio-plugins.6/)
and companion scripts and tools should be installed. The intention of this
collection is to easily locate all the essential resources.

Notice: for the audio setup with VST plugins, see the [Audio Products](https://github.com/rse/audio-setup/blob/master/audio-products.md)
of my [companion Audio-Setup](https://github.com/rse/audio-setup)!

### Base Application

- **OBS Studio** 32.1.2 (GPL)<br/>
  Open Broadcaster Software (Video Mixing Application)<br/>
  [Homepage](https://obsproject.com/)

### Essential Extensions

- **DistroAV (formerly OBS NDI)** 6.1.1 (GPL)<br/>
  Network Display Interface (NDI) input/output sources<br/>
  [Homepage](https://github.com/DistroAV/DistroAV/)

- **OBS WebSocket** 4.9.1-compat (GPL)<br/>
  OBSOLETE: Remote Control via OLD WebSockets (for StreamDeck, etc)<br/>
  [Homepage](https://github.com/Palakis/obs-websocket)

- **NVIDIA Video Effects SDK** 0.7.6 (Commercial)<br/>
  Video Effects for OBS Studio<br/>
  [Homepage](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

- **NVIDIA Audio Effects SDK** 1.6.1 (Commercial)<br/>
  Video Effects for OBS Studio<br/>
  [Homepage](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

### Plugins: Visual Effects

- **Zoominator** 1.5.0 (GPL)<br/>
  Comprehensive Auto-Zooming<br/>
  [Homepage](https://github.com/mmlTools/zoominator)

- **Composite Blur** 1.5.2 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-composite-blur)

- **Stroke Glow Shadow** 1.5.3 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-stroke-glow-shadow)

- **Advanced Masks** 1.5.4 (GPL)<br/>
  Comprehensive Mask Filters<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-advanced-masks)

- **Ahmanix Blur Filter** 1.1.1 (GPL)<br/>
  Comprehensive Blur Filter<br/>
  [Homepage](https://github.com/ashmanix/blur-filter-obs-plugin)

- **Background Removal** 1.3.7 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/royshil/obs-backgroundremoval)

- **Live Background Removal Lite** 3.9.3 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/kaito-tokyo/live-backgroundremoval-lite/)

- **Detect** 0.0.3 (GPL)<br/>
  AI-Based Object Detection (for Blurring and Zooming)<br/>
  [Homepage](https://github.com/locaal-ai/obs-detect)

- **Virtual Background** 1.2.0 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/kounoike/obs-virtualbg)

- **Asynchronous Source Duplication** 0.4.1 (GPL)<br/>
  Asynchronous Source Duplication<br/>
  [Homepage](https://github.com/norihiro/obs-async-source-duplication)

- **Shaderfilter** 2.6.0 (GPL)<br/>
  Shader Filter<br/>
  [Homepage](https://github.com/exeldro/obs-shaderfilter)

- **Shadertastic** 1.1.0 (GPL)<br/>
  Shader Filter<br/>
  [Homepage](https://www.shadertastic.com/)

- **Multi Source Effect** 0.2.1 (GPL)<br/>
  Combine two Sources with a Shader Effect<br/>
  [Homepage](https://github.com/norihiro/obs-multisource-effect)

- **Face Tracker** 0.9.1 (GPL)<br/>
  AI-Based Face Tracking Effect<br/>
  [Homepage](https://github.com/norihiro/obs-face-tracker/)

- **Gradient Source** 0.3.2 (GPL)<br/>
  Source for Rendered Gradient<br/>
  [Homepage](https://github.com/exeldro/obs-gradient-source)

- **SVG Source** 1.0.0 (GPL)<br/>
  Source for SVG Rendered<br/>
  [Homepage](https://github.com/FiniteSingularity/svg-source/)

- **Dynamic Delay** 0.1.4 (GPL)<br/>
  Dynamic Delay a Source<br/>
  [Homepage](https://github.com/exeldro/obs-dynamic-delay)

- **Time Warp Scan** 0.1.7 (GPL)<br/>
  Time Warp Scan Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-time-warp-scan)

- **Recursion Effect** 0.1.0 (GPL)<br/>
  Recursion Effect Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-recursion-effect)

- **Freeze Filter** 0.3.5 (GPL)<br/>
  Frame Freeze Source Filter<br/>
  [Homepage](https://github.com/exeldro/obs-freeze-filter)

- **LiveVisionKit Filter** 1.2.2 (GPL)<br/>
  Video Effect Filters: Video Stabilizer, Adaptive De-Blocker, Lens Correction, Calibration Tool<br/>
  [Homepage](https://github.com/Crowsinc/LiveVisionKit)

- **Text Slideshow** 2.0.0 (GPL)<br/>
  Text Slideshow<br/>
  [Homepage](https://github.com/jbwong05/obs-text-slideshow)

- **Text (GDI+) with Templates** 1.2.2 (GPL)<br/>
  Text with Mustache Template Variable Interpolation<br/>
  [Homepage](https://obsproject.com/forum/resources/text-gdi-with-templates.1878/)

- **Text (FreeType) with Templates** 1.0.0 (GPL)<br/>
  Text with Mustache Template Variable Interpolation<br/>
  [Homepage](https://github.com/marktheminer/text-freetype2-mustache)

- **URL/API Source** 0.4.0 (GPL)<br/>
  Fetch Live Data<br/>
  [Homepage](https://github.com/locaal-ai/obs-urlsource)

- **Markdown Source** 0.3.0 (GPL)<br/>
  Render Markup Text<br/>
  [Homepage](https://github.com/exeldro/obs-markdown)

- **HTML Source** 0.1.0 (GPL)<br/>
  HTML as a Source<br/>
  [Homepage](https://github.com/exeldro/obs-html-source)

- **3D Effect** 0.1.4 (GPL)<br/>
  3D Effect Filter<br/>
  [Homepage](https://github.com/exeldro/obs-3d-effect)

- **9-Slice Filter** 2.0.0 (GPL)<br/>
  9-Slice Scaling Filter<br/>
  [Homepage](https://github.com/cmdwtf/filter-9slice)

- **Frame Interleave** 0.2.0 (GPL)<br/>
  Interleaves Video Frames for non-Program display to reduce CPU/GPU usage<br/>
  [Homepage](https://github.com/norihiro/obs-frame-interleave-filter/)

- **OCR - Text Recognition** 0.0.8 (GPL)<br/>
  OCR Text Recognition with Tesseract<br/>
  [Homepage](https://github.com/locaal-ai/obs-ocr)

- **Encoder Region of Interest Editor** 1.1.1 (GPL)<br/>
  Encoder Optimization Hint for Region of Interest<br/>
  [Homepage](https://github.com/derrod/obs-roi-ui)

- **RTX SuperResolution** 1.2 (GPL)<br/>
  NVIDIA RTX Super Resolution Upscaler<br/>
  [Homepage](https://github.com/Bemjo/OBS-RTX-SuperResolution/)

- **Retro Effects** 1.0.2 (GPL)<br/>
  Many Retro Shader Effects<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-retro-effects/)

- **FreeFX** 0.12.0b299 (GPL)<br/>
  OBSOLETE: Powerful Filters (Shaders, etc) and Source Mirror Source (StreamFX Clone)<br/>
  [Homepage](https://github.com/xoxfaby/obs-StreamFX)

- **StreamFX** 1.0.0b610 (GPL)<br/>
  OBSOLETE: Powerful Filters (Shaders, etc) and Source Mirror Source<br/>
  [Homepage](https://github.com/Vhonowslend/StreamFX-Public)

- **Flip Clock** 1.0.0.1 (GPL)<br/>
  Flip Clock<br/>
  [Homepage](https://github.com/PeterCang/flip-clock/)

- **Stream My Heart** 1.0.4 (GPL)<br/>
  Webcam-based Heart Rate Detection<br/>
  [Homepage](https://github.com/Maciek03102003/StreamMyHeart)

- **Smart Gamma** 0.3.0 (GPL)<br/>
  Make dark scenes brighter<br/>
  [Homepage](https://github.com/mirkonz/smart-gamma/)

- **Flood Tuber** 1.1.0 (GPL)<br/>
  PNGTuber animations<br/>
  [Homepage](https://github.com/justflood/flood-tuber)

- **ArUco Source Move** 1.1.1 (GPL)<br/>
  OpenCV based ArUco Marker Detection (Augmented Reality)<br/>
  [Homepage](https://github.com/mVolpe94/aruco-source-move)

- **Adjustment Layer** 1.0.5 (GPL)<br/>
  Apply effect filters on an adjustment layer to all Sources placed behind it<br/>
  [Homepage](https://github.com/HoraiChan/obs-adjustment-layer)

- **Halsu Plugins for Streaming** 1.1.1 (GPL)<br/>
  Advanced Keying, Alpha Adjustment, Relighting effects<br/>
  [Homepage](https://github.com/Halsu/halsu-plugins-for-streaming)

### Plugins: Scene/Source Management

- **Scene Collection Manager** 0.2.0 (GPL)<br/>
  Filter/Backup/Restore Scene Collections<br/>
  [Homepage](https://github.com/exeldro/obs-scene-collection-manager)

- **Source Defaults** 1.2.0 (GPL)<br/>
  Source for Default<br/>
  [Homepage](https://github.com/CodeYan01/source-defaults/)

- **Source Clone** 0.2.3 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-clone)

- **Source Copy** 0.3.0 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-copy)

- **Replay Source** 1.8.1 (GPL)<br/>
  Instant Replay Sources from Memory<br/>
  [Homepage](https://github.com/exeldro/obs-replay-source)

- **Directory Watch Media** 0.7.0 (GPL)<br/>
  Filter you can add to Media Source to load the oldest/newest file in a directory<br/>
  [Homepage](https://github.com/exeldro/obs-dir-watch-media)

- **Scene Tree Folder** 0.2.0 (GPL)<br/>
  Dock for Scene Tree View<br/>
  [Homepage](https://github.com/DigitOtter/obs_scene_tree_view/)

- **Media Playlist Source** 0.1.3 (GPL)<br/>
  Media Source Playlist<br/>
  [Homepage](https://github.com/CodeYan01/media-playlist-source/)

- **xObsAsyncImageSource** 1.0 (GPL)<br/>
  Load Images Asynchronously<br/>
  [Homepage](https://github.com/YorVeX/xObsAsyncImageSource)

- **Source Defaults** 1.1.1 (GPL)<br/>
  Use Source for Defaults<br/>
  [Homepage](https://github.com/CodeYan01/source-defaults)

- **jrDockie** 1.5 (GPL)<br/>
  Save/Load Dock Settings<br/>
  [Homepage](https://github.com/dcmouser/obsPlugins/tree/main/jr/jrdockie)

- **Quick Access Utility (QAU)** 1.0.4 (GPL)<br/>
  Quick Source/Scene Access Dock<br/>
  [Homepage](https://github.com/FiniteSingularity/obs-quick-access-utility)

### Plugins: Scene/Source Control

- **Advanced Scene Switcher** 1.34.2 (GPL)<br/>
  Powerful Scene Switching<br/>
  [Homepage](https://obsproject.com/forum/resources/advanced-scene-switcher.395/)

- **Move (Transition)** 3.2.1 (GPL)<br/>
  Move Sources to New Position (During Scene Transition or for Face Tracking)<br/>
  [Homepage](https://github.com/exeldro/obs-move-transition)

- **Scene as a Transition** 1.3.1 (GPL)<br/>
  Use a Scene as a Transition<br/>
  [Homepage](https://github.com/andilippi/obs-scene-as-transition)

- **Transition Table** 0.3.1 (GPL)<br/>
  Override Scene Transitions<br/>
  [Homepage](https://github.com/exeldro/obs-transition-table)

- **Source Switcher** 0.4.4 (GPL)<br/>
  Source Switching between Multiple Sources<br/>
  [Homepage](https://github.com/exeldro/obs-source-switcher)

- **Media Controls** 0.5.0 (GPL)<br/>
  Control Dock for Media Playing<br/>
  [Homepage](https://github.com/exeldro/obs-media-controls)

- **Aitum Vertical** 1.6.3 (GPL)<br/>
  Vertical Canvas for vertical video layouts<br/>
  [Homepage](https://github.com/Aitum/obs-vertical-canvas)

- **Browser Transition** 0.1.3 (GPL)<br/>
  Use a Browser Source as a Transition<br/>
  [Homepage](https://github.com/exeldro/obs-browser-transition)

- **Scene as Transition** 1.2.1 (GPL)<br/>
  Use a Scene as a Transition<br/>
  [Homepage](https://github.com/andilippi/obs-scene-as-transition)

### Plugins: Streaming/Recording

- **Source Record** 0.4.8 (GPL)<br/>
  Individual Source Recording<br/>
  [Homepage](https://github.com/exeldro/obs-source-record)

- **Record Rename** 0.1.3 (GPL)<br/>
  Rename Recordings<br/>
  [Homepage](https://github.com/exeldro/obs-record-rename)

- **Virtual Cam** 2.1.2 (GPL)<br/>
  Standalone Version of OBS Virtual Camera (supports 4 targets)<br/>
  [Homepage](https://github.com/miaulightouch/obs-virtual-cam)

- **DroidCam Virtual Output** 0.2.2 (GPL)<br/>
  Kernel-Device-based (instead of DirectShow) Virtual Camera for Windows<br/>
  [Homepage](https://github.com/dev47apps/droidcam-obs-virtual-output)

- **Aitum Multistream** 1.0.7 (GPL)<br/>
  Multiple RTMP Outputs<br/>
  [Homepage](https://github.com/Aitum/obs-aitum-multistream)

- **Aitum Stream Suite** 1.1.1 (GPL)<br/>
  Multiple RTMP Outputs, Vertical Canvas<br/>
  [Homepage](https://github.com/Aitum/obs-aitum-stream-suite)

- **Branch Output** 1.0.9 (GPL)<br/>
  Multiple RTMP/SRT Outputs as a Source Filter<br/>
  [Homepage](https://github.com/OPENSPHERE-Inc/branch-output)

- **Multi RTMP** 0.5.0.4 (GPL)<br/>
  Multiple RTMP Outputs<br/>
  [Homepage](https://github.com/sorayuki/obs-multi-rtmp)

- **GStreamer** 0.4.1/1.24.3 (GPL)<br/>
  GStreamer Integration<br/>
  [Homepage](https://github.com/fzwoch/obs-gstreamer)

- **Virtual Cam Filter** 0.0.6 (GPL)<br/>
  OBSOLETE: Export Source Video To (Virtual) Camera Device<br/>
  [Homepage](https://github.com/exeldro/obs-virtual-cam-filter)

- **Main View Source** 0.3.0 (GPL)<br/>
  Duplicate Main View<br/>
  [Homepage](https://github.com/norihiro/obs-main-view-source)

- **Decklink Output Filter** 1.2.0 (GPL)<br/>
  Output Scenes/Sources to Blackmagic Decklink Cards<br/>
  [Homepage](https://github.com/cg2121/obs-decklink-output-filter)

- **AJA Output Filter** 0.2.3 (GPL)<br/>
  Output Scenes/Sources to AJA Devices<br/>
  [Homepage](https://github.com/norihiro/obs-aja-output-filter)

- **Audio Monitor** 0.10.0 (GPL)<br/>
  Export Source Audio To (Virtual) Speaker Device and Graphical Meter<br/>
  [Homepage](https://github.com/exeldro/obs-audio-monitor)

- **Master Level Meter** 1.0.2 (GPL)<br/>
  Show Volume Level of Master Tracks 1-6<br/>
  [Homepage](https://github.com/ShmKnd/MasterLevelMeter/)

- **Mix Track to Source** 1.0.2 (GPL)<br/>
  Create Audio Source of Master Tracks 1-6 for Filtering Master Tracks<br/>
  [Homepage](https://github.com/semnil/MixTrack2Source)

- **Reorderable Audio Mixer** 1.1.1 (GPL)<br/>
  Audio Mixer supporting Source Reordering<br/>
  [Homepage](https://github.com/TheTomCanuck/reorderable-audio-mixer)

- **Muted Notification** 1.0.2 (GPL)<br/>
  Play Sound when Parent Source is Muted<br/>
  [Homepage](https://git.vrsal.xyz/alex/urmuted)

- **VBAN Audio** 0.3.0 (GPL)<br/>
  Audio Source from and to VBAN (Audio over UDP) for VoiceMeeter<br/>
  [Homepage](https://github.com/norihiro/obs-vban/)

- **RTSP Server** 3.1.0 (GPL)<br/>
  Encode and publish RTSP/RTP Stream<br/>
  [Homepage](https://github.com/iamscottxu/obs-rtspserver)

- **Teleport** 0.7.6 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/fzwoch/obs-teleport)

- **xObsBeam** 1.1.0 (GPL)<br/>
  Send Frames within LAN (like NDI)<br/>
  [Homepage](https://github.com/YorVeX/xObsBeam)

- **OMTPlugin** 1.0.0.13 (GPL)<br/>
  Send Frames within LAN with Open Media Transport (OMT) (like NDI)<br/>
  [Homepage](https://github.com/openmediatransport/omtplugin/)

- **Antavore** 0.0.1 (GPL)<br/>
  OBSOLETE: Audio Watermark Generator<br/>
  [Homepage](https://github.com/adam-sporka/antavore-obs)

### Plugins: User Interface

- **Source Dock** 0.5.1 (GPL)<br/>
  Scene/Source as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-source-dock)

- **Scene Notes Dock** 0.3.0 (GPL)<br/>
  Scene/Source Notes as Dock<br/>
  [Homepage](https://github.com/exeldro/obs-scene-notes-dock)

- **Downstream Keyer** 0.4.4 (GPL)<br/>
  Scene-Independent Overlay Sources<br/>
  [Homepage](https://github.com/exeldro/obs-downstream-keyer)

- **Main View Source** 0.3.0 (GPL)<br/>
  Main View Duplication Source<br/>
  [Homepage](https://github.com/norihiro/obs-main-view-source/)

- **Draw** 0.3.1 (GPL)<br/>
  Scene Drawing in a Dock<br/>
  [Homepage](https://github.com/exeldro/obs-draw)

- **Instant Highlight Source Draw** 1.0.0 (GPL)<br/>
  Draw on Source<br/>
  [Homepage](https://github.com/mmlTools/draw-source)

- **OBS LowerThirdSwitcher** 2.0.0 (GPL)<br/>
  Scene-Based Lower Third Control<br/>
  [Homepage](https://github.com/levi-hrb/obs-plugin-lowerthirdswitcher)

- **Durchblick** 0.5.3 (GPL)<br/>
  Alternative Multiview<br/>
  [Homepage](https://obsproject.com/forum/resources/durchblick.1484)

- **Active Scene Dock** 0.1.2 (GPL)<br/>
  OBSOLETE: Show Preview/Program Duration<br/>
  [Homepage](https://github.com/layeh/obs-active-scene-dock)

### Plugins: Audio Input

- **ASIO** 3.2.1f (GPL)<br/>
  ASIO Audio Support<br/>
  [Homepage](https://github.com/Andersama/obs-asio)

- **atkAudio** 0.31.15 (GPL)<br/>
  VST3 Plugin Host for OBS<br/>
  [Homepage](https://www.atkaudio.com/products/atkaudio-plugin)

- **BlueCat Audio PatchWork** 2.72 (COM)<br/>
  VST3 Plugin Host (generic)<br/>
  [Homepage](https://www.bluecataudio.com/Products/Product_PatchWork/)

### Plugins: Audio Monitoring

- **Audio Video Sync Dock** 0.1.4 (GPL)<br/>
  Visualize Colors of Cameras for Debugging Purposes<br/>
  [Homepage](https://github.com/norihiro/obs-audio-video-sync-dock/)

- **Color Monitor** 0.9.5 (GPL)<br/>
  Visualize Colors of Cameras for Debugging Purposes<br/>
  [Homepage](https://github.com/norihiro/obs-color-monitor)

- **Loudness Dock** 0.5.0 (GPL)<br/>
  Audio EBU R 128 Loudness Meter<br/>
  [Homepage](https://github.com/norihiro/obs-loudness-dock/)

- **Master Level Meter** 1.0.2 (GPL)<br/>
  Audio Loudness Meter<br/>
  [Homepage](https://github.com/ShmKnd/MasterLevelMeter/)

- **Waveform** 1.8.0 (GPL)<br/>
  Audio Waveform Visualization<br/>
  [Homepage](https://github.com/phandasm/waveform)

- **Audio Waves** 2.0.0 (GPL)<br/>
  Audio Waveform Visualization<br/>
  [Homepage](https://github.com/mmlTools/audio-wave)

- **Scale To Sound** 1.2.5 (GPL)<br/>
  OBSOLETE: Scale a Source to a Sound<br/>
  [Homepage](https://github.com/Qufyy/obs-scale-to-sound)

- **Image Reaction** 1.3.0 (GPL)<br/>
  OBSOLETE: Switch Images to a Sound<br/>
  [Homepage](https://github.com/scaledteam/obs-image-reaction)

### Plugins: Audio Output

- **Asynchronous Audio Filter** 0.4.0 (GPL)<br/>
  Asynchronous Audio Filter<br/>
  [Homepage](https://github.com/norihiro/obs-async-audio-filter)

- **Audio Stems Recorder** 1.3.0 (GPL)<br/>
  Save All Audio Tracks as WAV files<br/>
  [Homepage](https://github.com/mmlTools/audio-stems-recorder)

- **Mute Filter** 0.4.0 (GPL)<br/>
  Mute Unwanted Audio<br/>
  [Homepage](https://github.com/norihiro/obs-mute-filter)

- **Audio Pan Filter** 0.2.3 (GPL)<br/>
  Stereo Panning<br/>
  [Homepage](https://github.com/norihiro/obs-audio-pan-filter)

- **CleanStream** 0.2.0 (GPL)<br/>
  Um-Removal<br/>
  [Homepage](https://github.com/locaal-ai/obs-cleanstream)

- **LocalVocal** 0.5.3 (GPL)<br/>
  Local OpenAI Whisper Transcription<br/>
  [Homepage](https://github.com/locaal-ai/obs-localvocal)

- **CloudVocal** 0.0.1 (GPL)<br/>
  Cloud Transcription<br/>
  [Homepage](https://github.com/locaal-ai/cloudvocal)

- **Squawk** 0.0.4 (GPL)<br/>
  Local Text-to-Speech Generation<br/>
  [Homepage](https://github.com/locaal-ai/obs-squawk)

- **Polyglot** 0.0.2 (GPL)<br/>
  Local LLM Text Translation<br/>
  [Homepage](https://github.com/locaal-ai/obs-polyglot)

- **BrAIn** 0.0.0 (GPL)<br/>
  Local LLM Engine<br/>
  [Homepage](https://github.com/locaal-ai/obs-brAIn)

### Plugins: Meta-Information

- **Info Writer** 2.7.1 (GPL)<br/>
  Write Timestamps and Information Text to Logfiles<br/>
  [Homepage](https://github.com/partouf/OBSInfoWriter/)

- **Chapter Marker** 1.0.3 (GPL)<br/>
  Write Timestamps to Video Recorded Files<br/>
  [Homepage](https://github.com/Davidj361/OBS-ChapterMarker)

- **StreamUP Chapter Marker Manager** 1.3.0 (GPL)<br/>
  Write Timestamps to Video Recorded Files<br/>
  [Homepage](https://github.com/StreamUPTips/obs-chapter-marker-manager)

- **Local Stream Markers** 1.10 (GPL)<br/>
  Write Stream Markers to CSV File<br/>
  [Homepage](https://obsproject.com/forum/resources/local-stream-marker.1457/)

### Plugins: Media Import

- **Media Playlist Source** 0.0.7 (GPL)<br/>
  Media Playlist<br/>
  [Homepage](https://github.com/CodeYan01/media-playlist-source)

- **Screenshot Filter** 1.5.2 (GPL)<br/>
  Source Screenshot Filter<br/>
  [Homepage](https://github.com/synap5e/obs-screenshot-plugin)

- **Better Screenshot** 1.2.0 (GPL)<br/>
  Source Screenshot Filter<br/>
  [Homepage](https://github.com/mmlTools/better-screenshot)

- **Ghostscript** 1.3 (GPL)<br/>
  OBSOLETE: PDF Rendering with Ghostscript<br/>
  [Homepage](https://github.com/nleseul/obs-ghostscript)

- **VNC Source** 0.6.2 (GPL)<br/>
  OBSOLETE: Display Remote Desktop via VNC<br/>
  [Homepage](https://github.com/norihiro/obs-vnc)

- **Spout Plugin** 1.8 (GPL)<br/>
  Import/Export of Textures to and from SPOUT2 compatible programs<br/>
  [Homepage](https://github.com/Off-World-Live/obs-spout2-plugin)

- **Soundboard** 2.0.0 (GPL)<br/>
  Play Sound Files<br/>
  [Homepage](https://github.com/cg2121/obs-soundboard)

- **Closed Captioning** 0.28 (GPL)<br/>
  Closed Captioning via Google Speech API<br/>
  [Homepage](https://github.com/ratwithacompiler/OBS-captions-plugin)

- **OBS Lottie** 1.1.1 (GPL)<br/>
  Play Lottie Animation Files<br/>
  [Homepage](https://github.com/GrandMastersOnline/obs-lottie)

- **DroidCam OBS Camera** 2.4.2 (GPL)<br/>
  Connect Mobile Phone (Android/iOS) as Camera to OBS Studio<br/>
  [Homepage](https://github.com/dev47apps/droidcam-obs-plugin)

- **OBS Streamlink** 0.4.1 (GPL)<br/>
  Receive Stream via Streamlink<br/>
  [Homepage](https://github.com/dd-center/obs-streamlink)

- **Streamlink** 7.3.0 (GPL)<br/>
  Receive Stream from Streaming Portals<br/>
  [Homepage](https://streamlink.github.io/)

### Plugins: Remote Control

- **PTZControl** 0.18.2 (GPL)<br/>
  PTZ Camera Control<br/>
  [Homepage](https://github.com/glikely/obs-ptz)

- **Command Source** 0.5.0 (GPL)<br/>
  Dummy Source to Execute Commands when Scene Switched<br/>
  [Homepage](https://github.com/norihiro/obs-command-source)

- **Input Overlay** 5.0.5 (GPL)<br/>
  Show Interactions<br/>
  [Homepage](https://github.com/univrsal/input-overlay)

- **Shutdown** 0.3.0 (GPL)<br/>
  Adds Shutdown Functionality to WebSocket API<br/>
  [Homepage](https://github.com/noris-plugins-for-obs/shutdown-plugin/)

### Remote Control Clients

- **Stream Deck** 6.3.0 (COMMERCIAL)<br/>
  Remote Control Deck for Android/iOS<br/>
  [Homepage](https://www.elgato.com/en/stream-deck)

- **Companion** 3.3.1 (OPEN SOURCE)<br/>
  Remote Control Deck for Elgato Streamdeck<br/>
  [Homepage](https://bitfocus.io/companion)

- **TouchOSC** 1.3.1.204 (COMMERCIAL)<br/>
  Remote Control Deck<br/>
  [Homepage](https://hexler.net/touchosc)

- **Touch Portal** 3.1.12 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://www.touch-portal.com)

- **Streamer.bot** 0.2.3 (FREEWARE)<br/>
  Remote Control Deck for OBS Studio<br/>
  [Homepage](https://streamer.bot/)

- **Sammi (formerly LioranBoard)** 2.0 (OPEN SOURCE)<br/>
  Remote Control Deck for OBS Studio<br/>
  [Homepage](https://sammi.solutions/)

- **OBS WebSocket JS** 5.0.5 (MIT)<br/>
  JavaScript Application Programming Interface (API) for OBS WebSockets API (for use from OBS docks)<br/>
  [Homepage](https://github.com/obs-websocket-community-projects/obs-websocket-js)

- **OBS WebSocket HTTP** 2 (GPL)<br/>
  Remote Control via HTTP (for OBS WebSocket)<br/>
  [Homepage](https://github.com/IRLToolkit/obs-websocket-http/)

- **OBS-Web** 5 (GPL)<br/>
  Remote Control via OBS WebSocket<br/>
  [Homepage](http://obs-web.niek.tv/)

- **OBS Simple HTTP Control** 1.1 (GPL)<br/>
  OBSOLETE: Remote Control via HTTP (for OBS WebSocket)<br/>
  [Homepage](https://obsproject.com/forum/resources/xobssimplehttpcontrol-simple-http-url-control-for-obs.1331/)

- **OBS Command** 1.6.3 (FREEWARE)<br/>
  Command-Line Interface (CLI) for OBS WebSockets API<br/>
  [Homepage](https://github.com/REALDRAGNET/OBSCommand)

- **MATRIC** 2.6.23 (FREEWARE)<br/>
  Remote Control Deck<br/>
  [Homepage](https://matricapp.com/)

- **NOOBS CMDR** 1.0.3 (FREEWARE)<br/>
  OBSOLETE: Macros for Scripting the OBS WebSockets API<br/>
  [Homepage](https://github.com/nuttylmao/NOOBS-CMDR)

- **Deckboard** 3.0.1 (OPEN SOURCE)<br/>
  Remote Control Deck for OBS<br/>
  [Homepage](https://deckboard.app/)

- **MIDIControl** 2.0.5 (FREEWARE)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/Etuldan/MidiControl)

- **CoyoteMIDI** 189 (FREEWARE)<br/>
  Convert MIDI Events into Keystrokes/Mouse Events<br/>
  [Homepage](https://coyotemidi.com/)

- **OBS MIDI MG** 3.1.5 (GPL)<br/>
  Remote Control OBS via MIDI<br/>
  [Homepage](https://github.com/nhielost/obs-midi-mg)

- **OSC for OBS** 3.1.3 (FREEWARE)<br/>
  Remote Control OBS via OSC<br/>
  [Homepage](https://github.com/jshea2/OSC-for-OBS)

- **CastMate** 0.4.9 (AGPL)<br/>
  Twitch/OBS Integration<br/>
  [Homepage](https://github.com/LordTocs/CastMate)

- **OBSwitcher** 0 (AGPL)<br/>
  OBS Remote Scene Switcher<br/>
  [Homepage](http://www.cvhvisuals.com/obswitcher.html)

- **Autostarter** 2.1.0 (GPL)<br/>
  Start programs automatically<br/>
  [Homepage](https://github.com/DaviBe92/Autostarter)

### Browser Sources

- **RSE Crop Control** 1.0.0 (GPL)<br/>
  Remote Crop-Filter Control<br/>
  [Homepage](https://github.com/rse/obs-crop-control)

- **RSE Birddog Camera Preset** 1.0.0 (GPL)<br/>
  Recall Birddog Camera Preset<br/>
  [Homepage](https://github.com/rse/obs-birddog-camera-preset/)

- **RSE Analog Clock** 1.6.2 (GPL)<br/>
  Nice Analog Clock<br/>
  [Homepage](https://github.com/rse/analogclock)

- **RSE Lower Thirds** 0.9.5 (GPL)<br/>
  Automatically-Controlled Lower Thirds<br/>
  [Homepage](https://github.com/rse/lowerthird)

- **VinciFlow** 3.7.0 (GPL)<br/>
  Lower-Thirds Engine
  [Homepage](https://github.com/mmlTools/vinci-flow)

- **Lower Thirds with Dockable Control Panel** 1.6 (GPL)<br/>
  Semi-Manually-Controlled Lower Thirds<br/>
  [Homepage](https://obsproject.com/forum/resources/animated-lower-thirds-with-dockable-control-panel.1057/)

- **WebRTC-Telestrator** 1.0.0 (GPL)<br/>
  Draw over Program<br/>
  [Homepage](https://github.com/BlankSourceCode/WebRTC-Telestrator)

- **IROS** 0.0.0 (GPL)<br/>
  Place Text and Images on Canvas<br/>
  [Homepage](https://obsproject.com/forum/resources/iros-flexible-and-remotly-controllable-stream-overlay.1863/)

- **Local Webserver** 1.0.0 (GPL)<br/>
  Run an embedded Webserver<br/>
  [Homepage](https://github.com/mmlTools/local-webserver)

### Lua Scripts

- **Lumetric Corrector** 1.2.0 (GPL)<br/>
  Professional Color Correction<br/>
  [Homepage](https://obsproject.com/forum/resources/lumetric-corrector.2137/)

- **Lobster** 0 (GPL)<br/>
  Simplified OBS Lua API<br/>
  [Homepage](https://obsproject.com/forum/resources/lobster-an-api-wrapper-to-simplify-writing-obs-scripts.1874/)

- **RSE OBS Scripts** 2022-03 (GPL)<br/>
  Clone Template Scene, Keyboard Event Filter, Production Information, Refresh Browser Sources, Source One of Many<br/>
  [Homepage](https://github.com/rse/obs-scripts)

- **Advanced Timer** 6.0.0 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://github.com/cg2121/obs-advanced-timer/)

- **Countdown Adaptive Time** 2.1 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://obsproject.com/forum/resources/count-down-adaptive-time-with-auto-recording-scene-switcher.719/)

- **Comprehensive Stopwatch & Countdown Timer** 5.9 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://obsproject.com/forum/resources/comprehensive-stopwatch-countdown-timer.1364/)

- **Ashmanix Countdown Timer** 2.1.1 (GPL)<br/>
  Flexible Timer<br/>
  [Homepage](https://github.com/ashmanix/obs-plugin-countdown/)

- **Libre Macros** 4.0.0 (GPL)<br/>
  Attach Lua Console Scripts to Sources<br/>
  [Homepage](https://github.com/upgradeQ/obs-libre-macros)

- **Filter Hotkeys** 1.0.2 (MPL)<br/>
  Allow Hotkeys to Toggle Source Filters<br/>
  [Homepage](https://github.com/upgradeQ/obs-filter-hotkeys)

- **Color Curves** 1.2 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/color-curves.1540/)

- **Clone Stamp** 1.2 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/clone-stamp.1535/)

- **Corner Pin** 1.4 (GPL)<br/>
  Four Corner Pin Transform Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/corner-pin.1474/)

- **Lens Flare** 1.4 (GPL)<br/>
  Lens Flare Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/lens-flare-2.1495/)

- **Lens Correction** 1.1.0 (GPL)<br/>
  Lens Correction Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/lenscorrector-professional.2089/)

- **Pan Zoom Rotate** 1.3 (GPL)<br/>
  Pan/Zoom/Rotate Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/pan-zoom-rotate.1489/)

- **Color Correction** 1.1 (GPL)<br/>
  Color Correction Effect Filter<br/>
  [Homepage](https://obsproject.com/forum/resources/3-axis-color-correction.1472/)

- **OBS Visca-over-IP Control** 2.6 (GPL)<br/>
  Control PTZ Cameras with VISCA-over-IP/UDP<br/>
  [Homepage](https://github.com/vwout/obs-visca-control)

- **Audio Status Monitor** 0.7 (GPL)<br/>
  Audio Status Monitoring Dock<br/>
  [Homepage](https://obsproject.com/forum/resources/audio-status-monitor.1381/)

- **Dynamic Source Grid Organization** 1.1 (GPL)<br/>
  Layout Sources of Scene in a Grid<br/>
  [Homepage](https://obsproject.com/forum/resources/dynamic-source-grid-organizer.2057/)

### Companion Audio Tools

- **Youlean Loudness Meter** 2.4.3 (FREEWARE)<br/>
  Audio Analyzer<br/>
  [Homepage](https://youlean.co/youlean-loudness-meter/)

- **OBS Audio Sync** 2019 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Video-Based)<br/>
  [Homepage](http://obsaudiosync.com/)

- **LoistoSYNC** 2021-05 (FREEWARE)<br/>
  Audio/Video Synchronization Tool (Browser-Source-Based)<br/>
  [Homepage](https://github.com/reaby/loistoSYNC)

- **Voice Attack** 1.14 (FREEWARE)<br/>
  Voice Control Commands<br/>
  [Homepage](https://voiceattack.com/)

- **Virtual Audio Cable (VAC)** 4.70 (COMMERCIAL)<br/>
  Virtual Audio Cable<br/>
  [Homepage](https://vac.muzychenko.net/en/)

- **VoiceMeeter Potato** 3.1.1.3 (COMMERCIAL)<br/>
  Audio Channel Mixer, Virtual Audio Cable<br/>
  [Homepage](https://voicemeeter.com/)

- **VB Audio Matrix** 1.0.1.0 (COMMERCIAL)<br/>
  Audio Router for ASIO/Windows/VAIO/VBAN devices<br/>
  [Homepage](https://vb-audio.com/Matrix/index.htm)

- **LoopMIDI** 1.0.16.27 (COMMERCIAL)<br/>
  Virtual MIDI Port<br/>
  [Homepage](https://www.tobias-erichsen.de/software/loopmidi.html)

- **OcenAudio** 3.14.3 (FREEWARE)<br/>
  Digital Audio Workstation (with VST support)<br/>
  [Homepage](https://www.ocenaudio.com/)

- **Audacity** 3.6.4 (GPL)<br/>
  Audio Editor<br/>
  [Homepage](https://www.audacityteam.org/)

- **Cantabile** 4-4206 (FREEWARE)<br/>
  VST Host<br/>
  [Homepage](https://www.cantabilesoftware.com/)

- **LightHost** 1.2.1 (GPL)<br/>
  VST Host<br/>
  [Homepage](https://github.com/rolandoislas/LightHost)

- **Auto-Duck** 3.0.0-RC4.1 (COMMERCIAL)<br/>
  Audio-Ducking: Volume Reduction for Speaking over Audio<br/>
  [Homepage](https://auto-duck.com/)

### Companion Video Tools

- **Lossless Cut** 3.64.0 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://github.com/mifi/lossless-cut/)

- **Shutter Encoder** 19.1 (FREEWARE)<br/>
  Audio/Video Cutter<br/>
  [Homepage](https://www.shutterencoder.com/)

- **Shotcut** 25.05.11 (GPL)<br/>
  Video Editor<br/>
  [Homepage](https://shotcut.org/)

- **Handbrake** 1.9.2 (GPL)<br/>
  Video Converter<br/>
  [Homepage](https://handbrake.fr/)

- **VLC** 3.0.21 (GPL)<br/>
  Video Player<br/>
  [Homepage](https://www.videolan.org/vlc/)

- **MPV** 3.0.21 (GPL)<br/>
  Video Player<br/>
  [Homepage](https://mpv.io/)

- **MediaInfo** 25.04 (GPL)<br/>
  Audio/Video Analyzer<br/>
  [Homepage](https://mediaarea.net/en/MediaInfo)

- **Blackmagicdesign DaVinci Resolve** 20.0.0 (COMMERCIAL, freely available)<br/>
  Video Editor<br/>
  [Homepage](https://www.blackmagicdesign.com/de/products/davinciresolve)

- **Kdenlive** 25.04.1 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://kdenlive.org/en/)

- **Vingester** 2.8.0 (GPL)<br/>
  Web Contents Ingesting Tool (NDI-enabled)<br/>
  [Homepage](https://vingester.app/)

- **Livemind Recorder** 0.9.4 (COMMERCIAL)<br/>
  NDI MultiViewer and Recorder<br/>
  [Homepage](https://livemind.tv/recorder/)

- **CamooZ** 7.4.2 (FREEWARE)<br/>
  Camera Settings Management<br/>
  [Homepage](https://webcamtool.de/)

- **CamRename** 0.3 (FREEWARE)<br/>
  Camera Device Renaming<br/>
  [Homepage](https://obsproject.com/forum/resources/camrename.1408/)

- **OBS Graphic Clock** 3.5 (FREEWARE)<br/>
  Graphical Clock (Window-Captured)<br/>
  [Homepage](https://obsproject.com/forum/resources/obsgraphicclock-skinnable-analog-watch-with-countdown.1373/)

- **VDO.Ninja** 0 (FREEWARE)<br/>
  Remote Guest Ingest<br/>
  [Homepage](https://vdo.ninja/)

- **SRC-Link** 0.7.4 (FREEWARE)<br/>
  Remote Guest Ingest<br/>
  [Homepage](https://src-link.live/)

- **OBS Notifier** 1.3.4 (FREEWARE)<br/>
  Desktop Notifications of OBS Studio Events<br/>
  [Homepage](https://github.com/DmitriySalnikov/OBSNotifier)

