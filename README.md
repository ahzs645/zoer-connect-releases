# Zoer Connect legacy update bridge

Current source and future WordPress update packages live in the public [Zoer Connect repository](https://github.com/ahzs645/zoer-connect) and its [GitHub Releases](https://github.com/ahzs645/zoer-connect/releases).

This repository remains available for installed connectors older than 0.5.2. Its `latest.json` feed is frozen at the qualified **0.5.2 migration bridge**. WordPress Plugins → Updates installs that bridge using the existing feed and verifies its ZIP SHA-256. After upgrading, the connector checks and downloads future updates directly from `zoer-connect` GitHub Releases.

Keep this repository public and its existing URLs available for sites that upgrade later. Historical ZIPs, versioned manifests and the final bridge are immutable. Future releases do not publish here or require its deploy key. No connection keys or WordPress site data are included.

Do not update the connector during an active website transfer. Automatic updates remain off unless a WordPress administrator enables them.
