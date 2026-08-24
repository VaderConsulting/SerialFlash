# SerialFlash

Access SPI Serial Flash memory with filesystem-like functions. SerialFlash provides low-latency, high performance access to SPI Flash memory with a filesystem-like interface. Familiar file-based functions, similar to the SD library, are used to access data. Original author: Paul Stoffregen. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 0.5. Upstream: <https://github.com/PaulStoffregen/SerialFlash>.

**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SerialFlash` | C++ / Arduino | library | Access SPI Serial Flash memory with filesystem-like functions |
| `CopyFromSD` | C++ / Arduino | example sketch | `examples/CopyFromSD/CopyFromSD.ino` |
| `CopyFromSerial` | C++ / Arduino | example sketch | `examples/CopyFromSerial/CopyFromSerial.ino` |
| `EraseEverything` | C++ / Arduino | example sketch | `examples/EraseEverything/EraseEverything.ino` |
| `ListFiles` | C++ / Arduino | example sketch | `examples/ListFiles/ListFiles.ino` |
| `MP3Player` | C++ / Arduino | example sketch | `examples/MP3Player/MP3Player.ino` |
| `RawHardwareTest` | C++ / Arduino | example sketch | `examples/RawHardwareTest/RawHardwareTest.ino` |
| `ReadBenchmark` | C++ / Arduino | example sketch | `examples/ReadBenchmark/ReadBenchmark.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/SerialFlash`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** Paul Stoffregen
- **library.properties name:** SerialFlash
- **Version:** 0.5
- **Upstream URL:** <https://github.com/PaulStoffregen/SerialFlash>
- **Category:** Data Storage
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
