# Changelog

## 1.2.0 (2026-11-26)

- New **Crate** style (key `5`, replaces Gramophone): your Liked songs and library as record spines on a shelf. Pull a record, drop it on the turntable and it plays; drag the tonearm to seek, tap the record to pause
- New **Constellation** style (key `6`): every sung word becomes a star, and each line forms its own constellation. `G` toggles the album-coloured edge light
- New **Pulse** edge-glow animation: equalizer halo, kick shockwaves and comets that run one lap per bar
- **Background play**: songs picked in search, Up Next or Crate start without Apple Music coming to the front
- **Smoother**: every command to Music runs in the background, so lyrics and animations no longer freeze; repeated seeks and volume drags send only the latest value
- **Lighter on your Mac**: the edge glow pauses behind full-screen immersive, the beat is smoothed every frame, and nothing on screen is redrawn unless it changed
- Favourite no longer stalls the app when a song changes

## 1.1.0 (2026-11-05)

- New **Gramophone** style (replaces Warp): every song starts with dragging the record onto the player, then the record, shockwaves, grooves and sparks react to the music
- New **Poster** style: each line printed as its own poster, with fitted type, colour fields and credits; the chorus prints on paper
- **Pop** redesigned: each word enters by what it is (punch, drop, stretch on held notes, burst on stressed words) and the next word is shown to sing along
- **Speaker** now fills the whole screen
- Animations react to bass, mids, highs and voice, timed to your speaker
- **Favourite** the playing song from immersive mode (♡, `F`, ⌘⌥F)
- **Add to playlist** from immersive mode (`P`), including new playlists; streaming songs are added to your library first
- **Karaoke**: turn the singer down live with Light, Medium and Strong levels (`K`, ⌘⌥K)

## 1.0.0 (2026-10-31)

First public release.

- Edge glow across every display, as one continuous gradient, with Static, Breathe, Flow and Chase animations
- Album-synced colors, presets and custom colors; Music Sync beat pulsing via BlackHole
- Floating lyrics bar with word-by-word timing (enhanced LRC when available, syllable-weighted estimates otherwise)
- Immersive mode with five lyric styles (Flow, Pop, Speaker, Poster, Warp) and four views (Full, Glass, StandBy, Mini)
- Mini player that floats while you work and slides back to full screen; auto StandBy when you step away
- Library and Apple Music catalog search that plays your pick directly, without leaving immersive mode
- Up Next queue for library and catalog songs: plays in order when a song ends, Next jumps to it
- Pause for voice assistants, dictation and calls, then resume
- Speaker fallback to the MacBook speakers when a Bluetooth speaker disconnects, and back when it returns
- Volume booster (+3 to +12 dB) with a limiter
- Bluetooth speaker delay correction and per-song timing nudges
- Lyrics retry automatically when the lyrics server is down
- One-command installer for Apple Silicon and Intel Macs
- Free for personal use
