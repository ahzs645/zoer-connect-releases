# Zoer Connect releases

This public repository distributes qualified Zoer Connect WordPress plugin ZIPs built from the private source repository. It contains no connection keys or WordPress site data.

`latest.json` identifies the newest qualified version and its ZIP SHA-256. Each `releases/vVERSION/` directory contains an immutable ZIP and matching `manifest.json`. WordPress 0.3.11 and later check this feed through the plugin's Update URI and verify the ZIP checksum before installation.

Use WordPress Plugins → Updates to install an available version. Do not update during an active website transfer.
