## AusAgentSmith

Building open-source tools for Usenet and peer-to-peer file transfer in Rust and Python.

### Projects

| Project | Description |
|---------|-------------|
| [Indexarr](https://indexarr.net/) | Distributed Usenet indexer |
| [rustnzb](https://www.rustnzb.dev/) | NZB downloader |
| [rustTorrent](https://rusttorrent.dev/) | BitTorrent client |
| [NoteTaker](https://notetakerapp.dev/) | Note-taking app |

### Libraries

**Python**

| Package | Description |
|---------|-------------|
| [pythonTorrentDHT](https://pypi.org/project/pythontorrentdht/) | Full BitTorrent mainline DHT implementation (BEP 5/9/10/51) |

**Rust — Usenet / NZB**

| Crate | Description |
|-------|-------------|
| `nzb-nntp` | NNTP protocol client |
| `nzb-core` | Core NZB types and database layer |
| `nzb-decode` | Article decoding |
| `nzb-postproc` | Post-processing pipeline |
| `rust-yenc-simd` | yEnc decoder with SIMD acceleration |
| `rust_par2` | PAR2 repair file handling |

**Rust — WebDAV / Usenet Streaming**

| Crate | Description |
|-------|-------------|
| `nzbdav-core` | Models, database, config, blob store |
| `nzbdav-rar` | Pure Rust RAR4/RAR5 header parser |
| `nzbdav-stream` | On-demand Usenet streaming |
| `nzbdav-pipeline` | NZB processing pipeline |
| `nzbdav-dav` | WebDAV server |
| `nzbdav-arr` | Sonarr/Radarr client and monitoring |
| `nzbdav-app` | CLI, SABnzbd API, WebSocket, frontend |

**Rust — BitTorrent**

| Crate | Description |
|-------|-------------|
| `librtbit` | Core BitTorrent library |
| `librtbit-peer-protocol` | Peer wire protocol |
| `librtbit-tracker-comms` | Tracker communication |
| `librtbit-dht` | DHT implementation |
| `librtbit-bencode` | Bencode serialization |
| `librtbit-lsd` | Local service discovery |
| `librtbit-upnp` | UPnP port mapping |

### Contact

ausagentsmith@proton.me | [Discord](https://discord.gg/pu6chSqpnJ)
