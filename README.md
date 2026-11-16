# voiceink-build

Cloud build pipeline for a free, personal-use build of VoiceInk.

- Upstream: https://github.com/Beingpax/VoiceInk (GPL-3.0), tag v2.27
- The workflow in .github/workflows/build-voiceink.yml checks out the upstream source on a GitHub macOS runner, builds it with the project-provided make local (ad-hoc signing), and publishes VoiceInk.app (zipped) to this repo Releases.
- Local-build limitations (same as building it yourself): no iCloud dictionary sync, no automatic updates.
