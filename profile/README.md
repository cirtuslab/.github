# CitrusLab

Small, MIT-licensed tools for closed-source media players — currently a set of **AIMP 5** plugins
written directly against its C++/COM SDK, which is the only way to extend the player.

| Project | | What it does |
|---|---|---|
| [AIMP-NCM](https://github.com/cirtuslab/AIMP-NCM) | `C++` | NetEase Cloud Music inside AIMP: cookie login with DPAPI-sealed credentials, eight quality tiers, playlist sync, and a loopback proxy that injects ID3v2 metadata into the stream |
| [AIMPLyricsSaver](https://github.com/cirtuslab/AIMPLyricsSaver) | `C++` | Fetches lyrics from four providers on playback, merges bilingual and word-timed lines, saves `.lrc` beside the audio |
| [aimp_desktop_lyrics](https://github.com/cirtuslab/aimp_desktop_lyrics) | `C++` | Desktop lyric overlay window for AIMP 5+ |
| [aimp-obs-now-playing](https://github.com/cirtuslab/aimp-obs-now-playing) | `Python` | Now-playing bridge for OBS and phones: browser source with themes, floating window, device-approved LAN page |
| [SongMetaFixer](https://github.com/cirtuslab/SongMetaFixer) | `Python` | Repairs audio metadata from NetEase / iTunes / MusicBrainz lookups |

Everything ships as release artifacts rather than source-only, every repository is MIT licensed,
and the C++ projects build for both x64 and x86 on hosted Windows runners on each push and pull
request.

Distributed under the MIT licence. Not affiliated with AIMP or with any music service; plugin
users are responsible for their own accounts and for the terms of the services they connect to.
