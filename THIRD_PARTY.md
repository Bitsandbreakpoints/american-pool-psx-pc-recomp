# Third-party code and pictures

The release (`american_pool.exe`) is built with the following open-source
code. The full licence texts are in the `licenses` folder of the release.

| Component | Licence | Used for |
|---|---|---|
| [Dear ImGui](https://github.com/ocornut/imgui) 1.92.9b | MIT | launcher and settings |
| [libchdr](https://github.com/rtissera/libchdr) (commit 47d7941) | BSD-3-Clause | reading `.chd` disc images |
| – zstd 1.5.7 | BSD-3-Clause (chosen from GPLv2/BSD) | CHD decoding |
| – LZMA SDK 26.02 (LzmaDec only) | public domain | CHD decoding |
| – miniz 3.1.2 | MIT | CHD decoding (zlib) |
| – dr_flac | public domain / MIT-0 | CHD decoding (FLAC) |
| [stb_image](https://github.com/nothings/stb) 2.30 | public domain / MIT | decoding the launcher picture (JPEG) |

It is compiled with [llvm-mingw](https://github.com/mstorsjo/llvm-mingw)
(clang and mingw-w64) and built with [ninja](https://ninja-build.org/);
neither is part of the program.

## Pictures

| Picture | Author | Licence | Source |
|---|---|---|---|
| Launcher background (built into the program, also in `images/launcher.png`) | MarkBuckawicki (own work, 2014) | CC0 1.0 (public domain) | [Wikimedia Commons: Billiards_Rack.JPG](https://commons.wikimedia.org/wiki/File:Billiards_Rack.JPG) |
| `images/in-game.png` | a picture of the game running in this port | the game's graphics are © their respective owners; shown for identification | – |

The game's own files (graphics, sound, data) are not included anywhere in
this repository or the release; they are read from the player's own disc.
