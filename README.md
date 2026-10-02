# PenguinOS Android 17 manifest overlay

This repository is the public source entrypoint for PenguinOS on Xiaomi Redmi Note 11 Pro 5G (`veux`) and POCO X4 Pro 5G (`peux`).

It is an overlay for a compatible AOSPA Android 17 base manifest. The overlay replaces only projects maintained by PenguinOS and leaves upstream platform projects to the chosen base manifest. Exact upstream bases and PenguinOS branch revisions are recorded in `pinned-sources.json`.

Vendor blobs are deliberately excluded from public source control. Use the companion `android_vendor_xiaomi_veux` extraction metadata and obtain compatible OEM firmware yourself.
