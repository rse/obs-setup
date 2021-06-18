
OBS Setup
=========

Version 1.0.4 (2021-06-18)

This is [Dr. Ralf S. Engelschall](https://engelschall.com)'s opinionated
list of software components for installing a full-featured
[Open Broadcaster Software (OBS) Studio](https://obsproject.com/) setup
under Windows 10 (x64). For this, beside the base application, multiple
[OBS Studio Plugins](https://obsproject.com/forum/resources/categories/obs-studio-plugins.6/)
should be installed.

### Base Application

- **OBS Studio** 27.0.1 (GPL)<br/>
  Open Broadcaster Software (Video Mixing Application)<br/>
  [Homepage](https://obsproject.com/)
  [Download](https://cdn-fastly.obsproject.com/downloads/OBS-Studio-27.0.1-Full-Installer-x64.exe)

### Base Extensions

- **OBS WebSocket** 4.9.1 (GPL)<br/>
  Remote Control via WebSockets (for StreamDeck, etc)<br/>
  [Homepage](https://github.com/Palakis/obs-websocket)
  [Download](https://github.com/Palakis/obs-websocket/releases/download/4.9.1/obs-websocket-4.9.1-Windows-Installer.exe)

- **OBS NDI** 4.9.0/4.9.1 (GPL)<br/>
  Network Display Interface (NDI) input/output sources<br/>
  [Homepage](https://github.com/Palakis/obs-ndi)
  [Download](https://github.com/Palakis/obs-ndi/releases/download/4.9.1/obs-ndi-4.9.0-Windows-Installer.exe)

- **NDI Tools** 4.6.2 (FREEWARE)<br/>
  Network Display Interface (NDI) Toolkit (dependency to OBS NDI)<br/>
  [Homepage](https://www.ndi.tv/tools/)
  [Download](https://downloads.ndi.tv/Tools/NDI%204%20Tools.exe)

### Essential Source/Scene/Filter Plugins

- **StreamFX** 0.10.1 (GPL)<br/>
  Powerful Filters (Shaders, etc) and Source Mirror Source<br/>
  [Homepage](https://github.com/Xaymar/obs-StreamFX)
  [Download](https://github.com/Xaymar/obs-StreamFX/releases/download/0.10.1/streamfx-windows-2019-0.10.1.0-gc8484f65.exe)

- **Advanced Scene Switcher** 1.13 (GPL)<br/>
  Powerful Scene Switching<br/>
  [Homepage](https://obsproject.com/forum/resources/advanced-scene-switcher.395/)
  [Download](https://github.com/WarmUpTill/SceneSwitcher/releases/download/1.13/SceneSwitcher.zip)
  
- **Move Transition** 2.4.3 (GPL)<br/>
  Move Sources to New Position During Scene Transition<br/>
  [Homepage](https://github.com/exeldro/obs-move-transition)
  [Download](https://obsproject.com/forum/resources/move-transition.913/version/3439/download?file=72272)

- **Media Controls** 0.3.4 (GPL)<br/>
  Control Dock for Media Playing<br/>
  [Homepage](https://github.com/exeldro/obs-media-controls)
  [Download](https://obsproject.com/forum/resources/media-controls.1032/version/3333/download?file=70772)

- **Source Switcher** 0.3.0 (GPL)<br/>
  Source Switching between Multiple Sources<br/>
  [Homepage](https://github.com/exeldro/obs-source-switcher)
  [Download](https://obsproject.com/forum/resources/source-switcher.941/version/3349/download?file=70930)

- **Source Record** 0.2.0 (GPL)<br/>
  Individual Source Recording<br/>
  [Homepage](https://github.com/exeldro/obs-source-record)
  [Download](https://obsproject.com/forum/resources/source-record.1285/version/3434/download?file=72153)

- **Virtual Cam Filter** 0.0.4 (GPL)<br/>
  Export Source Video To (Virtual) Camera Device<br/>
  [Homepage](https://github.com/exeldro/obs-virtual-cam-filter)
  [Download](https://obsproject.com/forum/resources/virtual-cam-filter.1142/version/3318/download?file=70648)

- **Audio Monitor** 0.7.1 (GPL)<br/>
  Export Source Audio To (Virtual) Speaker Device<br/>
  [Homepage](https://github.com/exeldro/obs-audio-monitor)
  [Download](https://obsproject.com/forum/resources/audio-monitor.1186/version/3101/download?file=66946)

### Useful Source/Scene/Filter Plugins

- **Source Copy** 0.1.3 (GPL)<br/>
  Scene/Source/Filter Copy & Paste<br/>
  [Homepage](https://github.com/exeldro/obs-source-copy)
  [Download](https://obsproject.com/forum/resources/source-copy.1261/version/3410/download?file=71875)

- **Downstream Keyer** 0.1.3 (GPL)<br/>
  Scene-Independent Overlay Sources<br/>
  [Homepage](https://github.com/exeldro/obs-downstream-keyer)
  [Download](https://obsproject.com/forum/resources/downstream-keyer.1254/version/3294/download?file=70171)

- **Transition Table** 0.1.5 (GPL)<br/>
  Override Scene Transitions<br/>
  [Homepage](https://github.com/exeldro/obs-transition-table )
  [Download](https://obsproject.com/forum/resources/transition-table.1174/version/3051/download?file=66260)

- **Directory Watch Media** 0.5.3 (GPL)<br/>
  Filter you can add to Media Source to load the oldest/newest file in a directory<br/>
  [Homepage](https://github.com/exeldro/obs-dir-watch-media)
  [Download](https://obsproject.com/forum/resources/directory-watch-media.801/version/3036/download?file=66027)

- **Gradient Source** 0.2.0 (GPL)<br/>
  Source for Rendered Gradient<br/>
  [Homepage](https://github.com/exeldro/obs-gradient-source)
  [Download](https://obsproject.com/forum/resources/gradient-source.1172/version/3406/download?file=71805)

- **Text Slideshow** 1.0.0 (GPL)<br/>
  Text Slideshow<br/>
  [Homepage](https://github.com/jbwong05/obs-text-slideshow)
  [Download](https://github.com/jbwong05/obs-text-slideshow/releases/download/v1.0.0/obs-text-slideshow-1.0.0-Windows-Installer-64-bit.exe)

- **Stereo Pan** 0.1.0 (GPL)<br/>
  Stereo Panning<br/>
  [Homepage](https://github.com/norihiro/obs-audio-pan-filter)
  [Download](https://github.com/norihiro/obs-audio-pan-filter/releases/download/0.1.0/obs-audio-pan-filter-0.1.0-windows.zip)

### Experimental Plugins

- **Background Removal - Portrait Segmentation** 0.3.0 (GPL)<br/>
  AI-Based Greenscreen Effect<br/>
  [Homepage](https://github.com/royshil/obs-backgroundremoval)
  [Download](https://github.com/royshil/obs-backgroundremoval/releases/download/v0.3.0-beta/obs-backgroundremoval-win64.zip)

- **Face Tracker** 0.1.2 (GPL)<br/>
  AI-Based Face Tracking Effect<br/>
  [Homepage](https://github.com/norihiro/obs-face-tracker/)
  [Download](https://github.com/norihiro/obs-face-tracker/releases/download/0.1.2/obs-face-tracker-0.1.2-Windows-Installer.exe)

### Useful Audio VST Plugins

- **Reaper ReaPlugs** 2.36 (FREEWARE)<br/>
  Audio VST Plugin-Suite<br/>
  Homepage: https://www.reaper.fm/reaplugs/
  [Download](https://www.reaper.fm/reaplugs/reaplugs236_x64-install.exe)

- **MFreeFXBundle** 4.16 (FREEWARE)<br/>
  Audio VST Plugin-Suite<br/>
  [Homepage](https://www.meldaproduction.com/MFreeFxBundle)
  [Download](https://www.meldaproduction.com/downloads/down?name=maudioplugins&platform=win&version=14.16&mirror=bunnycdn&url=https%3A%2F%2Fmeldaproduction.b-cdn.net%2Fdownload%2Fmaudioplugins%2Fmaudioplugins_14_16_setup.exe&checksum=905bf677fb7772fa9dabcdf27b71cff4e7bd9061)

- **Speachy** 1.0 (COMMERCIAL)<br/>
  Voice Audio "all-in-one" VST Plugin<br/>
  [Homepage](https://www.neverdieaudio.com)
  [Download](https://ccf23558-eb52-443e-bd9b-6383d021f85b.filesusr.com/archives/5f8f59_43f328c2f70043d29795b549ac0810ee.zip?dn=Speachy_1_0_setup_WIN.ZIP)

### Useful Extensions

- **RSE OBS Scripts** 2020-04 (GPL)<br/>
  Clone Template Scene, Keyboard Event Filter, Production Information, Refresh Browser Sources<br/>
  [Homepage](https://github.com/rse/obs-scripts)
  [Download](https://github.com/rse/obs-scripts/archive/refs/heads/master.zip)

### Useful Companion Tools

- **OBS Audio Sync** 2019 (FREEWARE)<br/>
  Audio/Video Synchronization Tool<br/>
  [Homepage](http://obsaudiosync.com/)
  [Download](https://share.hsforms.com/1GRBSRUxoTSCz56pblQR-WA8z4i)

- **VoiceMeeter Potato** 3.0.1.8 (COMMERCIAL)<br/>
  Audio Channel Mixer, Virtual Audio Cable<br/>
  [Homepage](https://vb-audio.com/Voicemeeter/potato.htm)
  [Download](https://download.vb-audio.com/Download_CABLE/Voicemeeter8Setup_v3018.zip)

- **Vingester** 2.2.4 (GPL)<br/>
  Web Contents Ingesting Tool (NDI-enabled)<br/>
  [Homepage](https://vingester.app/)
  [Download](https://github.oscdn.org/rse/vingester/2.2.4/Vingester-win-x64.zip)

- **Livemind Recorder** 0.9.4 (COMMERCIAL)<br/>
  NDI MultiViewer and Recorder<br/>
  [Homepage](https://livemind.tv/recorder/)
  [Download](https://dev.livemind.tv/download/?file=recorder/LivemindRecorder_v0.9.4.0.exe)

- **Lossless Cut** 3.36.0 (GPL)<br/>
  Video Cutter<br/>
  [Homepage](https://github.com/mifi/lossless-cut/)
  [Download](https://github.com/mifi/lossless-cut/releases/download/v3.36.0/LosslessCut-win.exe)

- **Shotcut** 21.05.01 (GPL)<br/>
  Video Editor<br/>
  [Homepage](https://shotcut.org/)
  [Download](https://github.com/mltframework/shotcut/releases/download/v21.05.01/shotcut-win64-210501.exe)

- **OcenAudio** 3.10.6 (FREEWARE)<br/>
  Digital Audio Workstation (with VST support)<br/>
  [Homepage](https://www.ocenaudio.com/)
  [Download](https://www.ocenaudio.com/start_download/ocenaudio64.exe)

- **Audacity** 3.0.2 (GPL)<br/>
  Audio Editor<br/>
  [Homepage](https://www.audacityteam.org/)
  [Download](https://github.com/audacity/audacity/releases/download/Audacity-3.0.2/audacity-win-3.0.2.exe)

- **Cantabile** 3-3686 (FREEWARE)<br/>
  VST Host<br/>
  [Homepage](https://www.cantabilesoftware.com/)
  [Download](https://download.cantabilesoftware.com/SetupCantabile-3686.exe)

- **LightHost** 1.2.1 (GPL)<br/>
  VST Host<br/>
  [Homepage](https://github.com/rolandoislas/LightHost)
  [Download](https://github.com/rolandoislas/LightHost/releases/download/v1.2.1/Light.Host.1.2.1.Win64.zip)

- **Handbrake** 1.3.3 (GPL)<br/>
  Video Converter<br/>
  [Homepage](https://handbrake.fr/)
  [Download](https://handbrake.fr/rotation.php?file=HandBrake-1.3.3-x86_64-Win_GUI.exe)

- **VLC** 3.0.14 (GPL)<br/>
  Video Player<br/>
  [Homepage](https://www.videolan.org/vlc/)
  [Download](https://get.videolan.org/vlc/3.0.14/win64/vlc-3.0.14-win64.exe)

