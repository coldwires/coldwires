## COLDWIRES

Systems programmer — network architecture, binary formats, game preservation.
C/C++, x86, protocol reverse engineering, authoritative server design.
Particular interest in server-side anti-cheat: I build the exploit first, then the architecture
that makes it irrelevant.

Remote · your@email · Open to: game security / anti-cheat, netcode, engine & preservation work

---

### ▍ Selected work

**[Authoritative multiplayer server](https://github.com/coldwires/DyeWarsProject)** — C++20 server, Unity client
Server owns all game state; client renders and predicts. Flat-grid spatial hash for O(1)
range queries, bidirectional visibility tracking for enter/leave events, dirty-flag
broadcast batching, Lua hot-reload for game logic. Sustains 2,000 simulated clients at
20 TPS (~40–50ms tick, single host). Protocol and architecture fully documented.

**ONWIND** *(active)* — clean-room reconstruction of a 20-year-old MMO server core.
Protocol recovered through packet analysis and client behavior; rebuilt against a
documented message spec in place of the original's ad-hoc encryption. Write-up in progress.

**Tooling** — map editors and unpackers built on reverse-engineered archive formats.
Headless client and stat logger feeding a live leaderboard.

---

### ▍ Toolkit

- **Languages** — `C++` `C` `x86 asm` · `C#` `Lua`
- **Reverse engineering** — `Ghidra` `IDA` `x64dbg` `Wireshark`
- **Networking** — authoritative server design · binary protocol design · custom serialization · async I/O
- **Systems & build** — `CMake` `vcpkg` `asio` `SQLite` `sol2` `spdlog`
- **Engines** — `Unity` `Unreal` `FNA` `MonoGame`

---

### ▍ Practice

Clean-room throughout — analysis on legally obtained copies, no proprietary assets or
code redistributed, specifications documented independently of original source.
Preservation-oriented: the goal is that these systems stay runnable.

Some work is under NDA or otherwise not public. Happy to discuss approach and
architecture directly.

---

*The real work is in the repos.*
