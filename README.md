# Awesome-Secure-File-Transfer-CLI-Data-Sharing

# Top Secure File Transfer & CLI Data Sharing Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on End-to-End Encrypted File Transfers, Peer-to-Peer CLI Utilities, Self-Hosted WeTransfer Alternatives & Ephemeral Data Sharing*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted file transfer platforms** and **open-source GitHub projects** for **Secure File Transfer & CLI Data Sharing**. These tools allow developers, sysadmins, and privacy-conscious users to send large files and folders directly between computers with end-to-end encryption (PAKE/WebRTC/Noise), NAT traversal, self-destructing links, and zero cloud storage tracking.

**Examples** include schollz/croc, Magic Wormhole, LocalSend, PairDrop, Send (Firefox Send fork), Pingvin Share, Gokapi, OnionShare, Syncthing, qrcp, WeTransfer, Smash, Filemail, Send Anywhere, SwissTransfer, Wormhole.app, Tresorit Send, Dropbox Transfer, Box File Transfer, and TransferNow.

**Open-source emphasis**: This list heavily expands on active open-source CLI peer-to-peer transfer utilities, cross-platform LAN/WebRTC sharing apps, Tor-routed anonymous file droppers, and self-hosted ephemeral file-sharing servers — ideal for engineers, researchers, and teams transferring sensitive archives, datasets, and secrets safely.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[WeTransfer](https://wetransfer.com)**  
  Popular cloud file-transfer service enabling quick link or email-based sharing of large files with password protection, expiry dates, and download tracking.

- **[SwissTransfer](https://swisstransfer.com)**  
  Privacy-focused file transfer service hosted in Switzerland by Infomaniak allowing free encrypted transfers up to 50 GB without registration.

- **[Wormhole (Wormhole.app)](https://wormhole.app)**  
  End-to-end encrypted, browser-based ephemeral file sharing platform utilizing WebRTC peer-to-peer streaming and zero-knowledge cloud storage up to 10 GB.

- **[Tresorit Send](https://tresorit.com)**  
  Zero-knowledge, end-to-end encrypted file-sharing service built by Tresorit featuring access logs, download limits, and Swiss/EU data residency.

- **[Smash](https://fromsmash.com)**  
  Cloud file transfer platform with no file-size limits, custom branding, password protection, and regional server selection.

- **[Filemail](https://filemail.com)**  
  High-speed file transfer service utilizing UDP acceleration alongside web, desktop, and CLI clients for large media and enterprise deliveries.

- **[Send Anywhere](https://send-anywhere.com)**  
  Cross-platform file sharing service using 6-digit one-time security keys for direct peer-to-peer device transfers or temporary cloud links.

- **[Dropbox Transfer](https://dropbox.com)**  
  Managed large-file delivery feature within Dropbox offering customizable download pages, password controls, expiration dates, and view notifications.

- **[Box File Transfer / Box Shield](https://box.com)**  
  Enterprise cloud content sharing platform with granular link permissions, watermarking, expiration policies, and compliance auditing.

- **[TransferNow](https://transfernow.net)**  
  Hosted secure file transfer service offering encrypted storage, custom share links, download receipts, and team workspaces.


## Open-Source GitHub Projects

- **[croc (schollz/croc)](https://github.com)**  
  Ultra-fast, cross-platform CLI tool written in Go that easily and securely sends files and folders between any two computers using PAKE end-to-end encryption, relay NAT traversal, and resume support.

- **[Magic Wormhole (magic-wormhole/magic-wormhole)](https://github.com)**  
  Iconic Python CLI utility and protocol for transferring arbitrary-sized files, directories, and short text snippets from one computer to another using human-pronounceable one-time codes.

- **[wormhole-william (psanford/wormhole-william)](https://github.com)** & **[magic-wormhole.rs (magic-wormhole/magic-wormhole.rs)](https://github.com.rs)**  
  Standalone, single-binary Go and Rust implementations of the Magic Wormhole protocol with zero Python runtime dependencies.

- **[LocalSend (localsend/localsend)](https://github.com)**  
  Cross-platform, open-source AirDrop alternative built with Flutter that securely shares files and messages over local Wi-Fi using REST APIs and HTTPS/TLS without internet access.

- **[PairDrop (schlagmichdoch/PairDrop)](https://github.com)**  
  Self-hostable, browser-based peer-to-peer file sharing application (maintained fork of Snapdrop) using WebRTC with persistent device pairing and temporary public rooms.

- **[Send — Community Fork of Firefox Send (timvisee/send)](https://github.com)**  
  Simple, private, self-hosted file sharing web application with client-side end-to-end encryption, download count limits, and automatic link expiration.

- **[Pingvin Share (stonith404/pingvin-share)](https://github.com)**  
  Modern, self-hosted file sharing platform (WeTransfer alternative) supporting chunked large-file uploads, reverse-share upload links, password protection, and S3 backends.

- **[Gokapi (Forceu/Gokapi)](https://github.com)**  
  Lightweight, self-hosted file sharing server written in Go featuring client-side/server-side encryption, API/CLI upload support, and auto-expiring links.

- **[OnionShare (onionshare/onionshare)](https://github.com)**  
  Open-source GUI and CLI tool that securely and anonymously shares files, hosts dropboxes, and serves static sites directly from your computer over the Tor network as `.onion` services.

- **[Syncthing (syncthing/syncthing)](https://github.com)**  
  Continuous, decentralized, peer-to-peer file synchronization tool written in Go with mutual TLS authentication, NAT traversal, and zero central servers.

- **[qrcp (claudiodangelis/qrcp)](https://github.com)**  
  Fast CLI tool written in Go that transfers files over local Wi-Fi between a terminal and mobile phone by rendering a scannable QR code directly in the shell.

- **[transfer.sh (dutchcoders/transfer.sh)](https://github.com)**  
  Developer-friendly, self-hostable file sharing service engineered for instant `curl --upload-file` transfers directly from the command line with GPG encryption support.

- **[rclone (rclone/rclone)](https://github.com)**  
  Swiss-army knife CLI utility ("rsync for cloud storage") featuring built-in `crypt` end-to-end encryption and `rclone serve` (HTTP/WebDAV/SFTP) for direct terminal data sharing.

### Additional Strong Open-Source Options

- **[age (FiloSottile/age)](https://github.com)** & **[rage (str4d/rage)](https://github.com)** — Simple, modern, auditable file encryption CLI tools (Go and Rust) ideal for encrypting archives before sharing over any channel.
- **[ffsend (timvisee/ffsend)](https://github.com)** — Full-featured Rust CLI client for interacting with Firefox Send / `timvisee/send` instances from the terminal.
- **[PSitransfer (psi-4ward/psitransfer)](https://github.com)** — Simple, open-source self-hosted file sharing solution with resumable uploads and bucket expiration.
- **[Zipline (diced/zipline)](https://github.com)** — Fast, self-hosted ShareX / file upload server with URL shortening, password protection, and chunked uploads.
- **[iroh (n0-computer/iroh)](https://github.com)** — Modular Rust networking library and `iroh-blobs` CLI for fast, QUIC-based peer-to-peer content-addressed data transfer.
- **[Taildrop (Tailscale Open-Source Client)](https://github.com)** — Peer-to-peer file transfer utility built into Tailscale (`tailscale file cp`) for sending files across your WireGuard mesh devices.

**Frameworks for building custom systems**: Combine **croc** or **Magic Wormhole** for instant terminal-to-terminal encrypted transfers, **LocalSend** + **qrcp** for mobile-to-desktop LAN sharing, and **Pingvin Share** or **timvisee/send** behind Caddy/Nginx for self-hosted external client file delivery.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- When transferring sensitive credentials, keys, or proprietary datasets over public relay servers (`croc`, `magic-wormhole`), verify the recipient's PAKE code/fingerprint out-of-band or run your own self-hosted relay instance.
- Self-hosted file sharing web apps (`Pingvin Share`, `Gokapi`, `Send`) exposed to the public internet should enforce HTTPS, upload size quotas, authentication for uploaders, and automatic file expiration policies.

---

**Made for sysadmins, security engineers, terminal power users, and open-source developers.**  
Let's make secure file transfer and CLI data sharing fast, encrypted, and open to everyone.
