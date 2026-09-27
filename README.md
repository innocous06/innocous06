<div align="center">

<img src="header.svg" width="100%" alt="innocous" />

</div>

```bash
~ whoami
  innocous

~ cat focus.txt
  • Database Architecture & Transactional Schemas
  • Zero-Dependency Encrypted VPN Protocols
  • Cloud Pipelines & Subprocess Automation
  • Distributed Systems & Consensus Protocols
```

---

### `technical stack`

<table>
<tr>
<td width="22%"><b><font color="#c9654a">Languages</font></b></td>
<td>

![Go](https://img.shields.io/badge/Go-18181f?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-18181f?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-18181f?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-18181f?style=flat-square&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/-18181f?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-18181f?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/-18181f?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-18181f?style=flat-square&logo=javascript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-18181f?style=flat-square&logo=gnubash&logoColor=white)

</td>
</tr>
<tr>
<td><b><font color="#c9654a">Networking & Sec</font></b></td>
<td>

![mTLS](https://img.shields.io/badge/mTLS_Validation-c9654a?style=flat-square&logoColor=white)
![TCP/UDP](https://img.shields.io/badge/TCP%2FUDP_Sockets-18181f?style=flat-square&logoColor=white)
![VPN](https://img.shields.io/badge/VPN_Protocol_Design-18181f?style=flat-square&logoColor=white)
![DPI](https://img.shields.io/badge/DPI_Evasion-18181f?style=flat-square&logoColor=white)
![QUIC](https://img.shields.io/badge/QUIC-18181f?style=flat-square&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-18181f?style=flat-square&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-18181f?style=flat-square&logo=nginx&logoColor=white)
![gomobile](https://img.shields.io/badge/gomobile-18181f?style=flat-square&logoColor=white)

</td>
</tr>
<tr>
<td><b><font color="#c9654a">Data & Storage</font></b></td>
<td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18181f?style=flat-square&logo=postgresql&logoColor=white)
![Relational Schemas](https://img.shields.io/badge/Relational_Schemas-18181f?style=flat-square&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore_NoSQL-18181f?style=flat-square&logo=firebase&logoColor=white)
![Indexing](https://img.shields.io/badge/Indexing_%26_Schemas-18181f?style=flat-square&logoColor=white)
![GPU Pipelines](https://img.shields.io/badge/GPU_Pipelines_%28cuML%2FCuPy%29-c9654a?style=flat-square&logo=nvidia&logoColor=white)

</td>
</tr>
<tr>
<td><b><font color="#c9654a">Web & Cloud</font></b></td>
<td>

![React](https://img.shields.io/badge/React-18181f?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-18181f?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18181f?style=flat-square&logo=nodedotjs&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-c9654a?style=flat-square&logo=oracle&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_APIs-18181f?style=flat-square&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Systems-18181f?style=flat-square&logo=linux&logoColor=white)
![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-18181f?style=flat-square&logo=cloudflarepages&logoColor=white)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow_Lite-18181f?style=flat-square&logo=tensorflow&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-18181f?style=flat-square&logoColor=white)

</td>
</tr>
</table>

---

### `featured engineering`

<table>
<tr>
<td width="50%" valign="top">

#### [`raft-kv`](https://github.com/innocous06/raft-kv) &nbsp; ![Go](https://img.shields.io/badge/Go-c9654a?style=flat-square&logo=go&logoColor=white)
Fault-tolerant distributed key-value store implementing Raft consensus from first principles - leader election, log replication, snapshot installation, and a checksummed write-ahead log with crash recovery, all built with zero consensus libraries.
* **Verification:** Chaos-injection harness simulating partitions, node crashes, and packet loss; linearizability checker confirms zero stale reads.
* **Stack:** `Go` · `Raft Consensus` · `WAL` · `CRC32` · `Chaos Testing`

</td>
<td width="50%" valign="top">

#### [`entity-linker`](https://github.com/innocous06/entity-linker) &nbsp; ![Python](https://img.shields.io/badge/Python-c9654a?style=flat-square&logo=python&logoColor=white)
GPU-accelerated record-linkage pipeline matching 1M+ noisy e-commerce listings for a team hackathon challenge - built solo end-to-end after confirming the team's hardware couldn't clear the evaluation threshold.
* **Scale:** Two-tier blocking (brand partition + MinHash LSH) cuts 500B naive comparison pairs to under 8M - a 99.998% reduction - while holding >98.5% recall.
* **Stack:** `Python` · `cuML` · `CuPy` · `MinHash LSH` · `RapidFuzz` · `TF-IDF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [`shadowlink`](https://github.com/innocous06/shadowlink) &nbsp; ![Rust](https://img.shields.io/badge/Rust-c9654a?style=flat-square&logo=rust&logoColor=white) (+ [`tunnel`](https://github.com/innocous06/tunnel), ![Go](https://img.shields.io/badge/Go-c9654a?style=flat-square&logo=go&logoColor=white))
DPI-resistant VPN tunnel with TLS SNI camouflage and mutual TLS - built independently in both Rust and Go to compare a memory-safety-first design against a raw-speed QUIC design.
* **Latency:** **20-50ms** domestic, ~230ms transatlantic (Go build, OCI nodes).
* **Stack:** `Rust` · `Go` · `QUIC` · `mTLS` · `ChaCha20-Poly1305` · `Curve25519` · `gomobile`

</td>
<td width="50%" valign="top">

#### [`NoiseStash`](https://github.com/innocous06/NoiseStash) &nbsp; ![Kotlin](https://img.shields.io/badge/Kotlin-c9654a?style=flat-square&logo=kotlin&logoColor=white)
On-device Android sound-dose tracker - classifies ambient noise and calculates cumulative OSHA/NIOSH exposure in real time, with zero audio ever leaving the device.
* **Efficiency:** Dual-rate architecture gates ML inference behind an amplitude threshold, keeping CPU under 3%.
* **Stack:** `Kotlin` · `Jetpack Compose` · `TensorFlow Lite (YAMNet)` · `Room/SQLite`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [`netpulse`](https://github.com/innocous06/netPulse) &nbsp; ![Node.js](https://img.shields.io/badge/Node.js-c9654a?style=flat-square&logo=nodedotjs&logoColor=white)
Self-hosted network diagnostics suite measuring real bandwidth, jitter, and packet loss - built to defeat the compression and caching tricks that inflate results on commercial speed tests.
* **Precision:** 50Hz WebSocket telemetry for sub-millisecond RTT sampling; confirmed 1.0x compression ratio on payloads.
* **Stack:** `Node.js` · `Express` · `WebSockets` · `Nginx` · `Cloudflare Pages`

</td>
<td width="50%" valign="top">

#### [`HyperShare`](https://github.com/innocous06/HyperShare) &nbsp; ![Node.js](https://img.shields.io/badge/Node.js-c9654a?style=flat-square&logo=nodedotjs&logoColor=white)
High-speed peer-to-peer file transfer engine for direct Wi-Fi 6 streaming - skips TLS handshakes and multipart parsing entirely to get out of the way of raw throughput.
* **Throughput:** Sustained **87 MB/s** direct LAN transmission speed.
* **Stack:** `Node.js` · `Express` · `Wi-Fi 6` · `pkg Executable`

</td>
</tr>
</table>

> *[View all repositories →](https://github.com/innocous06?tab=repositories)*

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-c9654a?style=for-the-badge&logoColor=white)](https://url.600266.xyz/portfolio)
&nbsp;
&nbsp;
[![Email](https://img.shields.io/badge/Email-18181f?style=for-the-badge&logo=maildotru&logoColor=c9654a)](mailto:innocous@duck.com)

<br>

<img src="https://komarev.com/ghpvc/?username=innocous06&style=flat-square&color=c9654a&label=profile+views" />

<br>

```
~ echo "innocous was here" ▌
```

</div>
