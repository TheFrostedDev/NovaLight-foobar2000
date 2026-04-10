# NovaLight-foobar2000
a vibrant and modular foobar2000-64bit theme built on ColumnsUI with some JSplitter elements

built from my own personal theme ive used for a while with new custom tab manager :3

<img width="1920" height="1032" alt="Main Player View" src="https://github.com/user-attachments/assets/23e9bc70-a4de-4542-be51-f25cd3c65cf0" />

# Install Instructions
1) Install foobar2000 **portable** from https://www.foobar2000.org/
2) Install LT Saeada font from fonts folder
3) Extract and copy profile and encoders folder into main foobar2000 folder
4) Enjoy ^_^

# NovaSplitter
- Acts as a main container for ColumnsUI panels
- Menu button in top-left corner to access topbar menu actions
- Panels accessible on the left
- "Mini mode" and Preferences shortcuts in bottom-left
- Default Panels: Player, Playlist Editor, Albums, Tagging, Spectrogram

### Player View

<img width="640" height="344" alt="Main Player View" src="https://github.com/user-attachments/assets/23e9bc70-a4de-4542-be51-f25cd3c65cf0" />


### Playlist Editor

<img width="640" height="516" alt="Playlists" src="https://github.com/user-attachments/assets/dbf8be7a-ee4d-43a6-b80b-1beb2c59a999" />


### Albums Grid View

<img width="868" height="344" alt="Albums" src="https://github.com/user-attachments/assets/35ef9999-51ba-4cd0-a204-c864a05a082f" />


### Tagging View

<img width="640" height="344" alt="Tagging" src="https://github.com/user-attachments/assets/92701735-a414-4ae3-a40e-dfbe1fce7964" />

## Customisation

- Add panels inside NovaSplitter

<img width="478" height="388" alt="ColumnsUI Editing" src="https://github.com/user-attachments/assets/59769e64-6168-486f-b2f0-fe1083b30630" />

- Use naming scheme to select icon and preserve ordering:

> \#-{NAME}_{ICON NAME}

- or for mini panels:
  
> \#-MINI-{NAME}_{ICON NAME}

- Set of supported icons (from lucide.dev):
> album, audio-lines, audio-waveform, book-headphones, book, bookmark, captions, cat, chart-area, chart-bar-decreasing, chart-column-stacked, chart-column, chart-line, chart-no-axes-column, chart-no-axes-gantt, chart-pie, chart-scatter, circle-play, clock-fading, clock, command, component, Default, disc-3, disc-album, download, drama, expand, file-check, file-music, file-search, file-user, folder, funnel, globe, heart, house, info, keyboard-music, list-end, list-filter-plus, list-filter, list-music, list-ordered, list-plus, list-start, list-video, mic-vocal, music-2, music-3, music-4, music, radio-tower, search, settings-2, shrink, sliders-horizontal, sliders-vertical, star, tag, tags, upload, user-round-search, user-round, users-round, wand-sparkles

## Mini mode

- Accessed by button in bottom-left, return by button in top-left in mini mode
- Ensure foobar is in windowed mode before toggling it (or it messes with the scaling a little)
- Currently not able to support always on top or automatically setting to windowed mode (looking for solution that doesnt mess with window snapping)

<img width="520" height="217" alt="MiniPlayer" src="https://github.com/user-attachments/assets/c8fcf801-e2ed-4c5b-b163-63ff4b1c890c" />

<img width="520" height="217" alt="MiniPlaylist" src="https://github.com/user-attachments/assets/86360494-61b7-4acc-9afe-9ca9518522d5" />

# Details
## Components List
- Columns UI (foo_ui_columns)
- FFmpeg Decoder Wrapper (foo_input ffmpeg)
- JSplitter (foo_uie_jsplitter)
- Masstagger (foo_masstag)
- Playlist Fix (foo_playlist_fix)
- Queue Viewer (foo_queue_viewer)
- Run services (foo_run)
- Spectrum Analyzer (foo_vis_spectrum_analyzer)
- Waveform Minibar (foo_wave_minibar_mod)

## JSplitter Packages
- NovaSplitter
- NovaGridView (Modified version of JS Smooth Browser by Br3tt)
- NovaPlaylistMini (Modified version of JS Smooth Playlist by Br3tt, optimised for smaller screen spaces)
- NovaVolumeSlider (Modified version of sample volume slider by marc2003)
