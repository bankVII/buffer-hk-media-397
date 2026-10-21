# Hack ธรรม reusable media host

This is the existing media repository, renamed from `buffer-hk-media-397`.
Use this repository for every episode; never create episode-specific repositories.

Store only numbered Final video renders under `media/`. Before scheduling, verify
the file content, an HTTPS `video/mp4` response with nonzero Content-Length, and a
successful byte-range request. Remove media from the current branch after all
dependent Buffer posts have been confirmed sent. Keep pending-post sources.

Public base: https://bankvii.github.io/buffer-hk-media-host/media/
