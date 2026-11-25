# SEAMS copy of microsoft/onnxruntime-swift-package-manager

`microsoft/onnxruntime-swift-package-manager` was removed from GitHub around 2026-11-17, and its
binaries on `download.onnxruntime.ai` are no longer served. SEAMS keeps this copy so Luna for macOS
(seamsai/mac-agent) keeps building. Not affiliated with or endorsed by Microsoft. MIT licensed (see LICENSE).

- History up to tag `1.24.2` (`b7fb7f7dea8a2469e6335d95a61b8f36d0dc83b2`) is Microsoft's, unmodified.
- Tag `1.24.2-seams.1` adds one commit: the two binary targets in `Package.swift` now download from this
  repository's release `1.24.2-seams.1` instead of `download.onnxruntime.ai`. No code changed.
- The release zips hold Microsoft's 1.24.2 / extensions 0.13.0 pod archives as SwiftPM downloaded and
  verified them (against Microsoft's checksums `f7100a99…` and `346522d1…`) on 2026-09-27, before the
  removal, re-zipped with their contents unchanged. Their new SwiftPM checksums are in `Package.swift`.
