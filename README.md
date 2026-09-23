# Bard model host

First-party binary releases for the models curated by Bard.

These files are redistributed from the upstream projects named in each release's
manifest. The application catalog records the upstream repository, revision,
license, size, and SHA-256 for every file. Bard's source code does not imply
ownership of third-party model weights.

## Release contents

| Bard role | Asset | Upstream model | Quantization |
| --- | --- | --- | --- |
| Fast multilingual | `ggml-small-q8_0.bin` | Whisper small | Q8_0 |
| Best English | `ggml-large-v3-turbo-q5_0.bin` | Whisper large-v3 turbo | Q5_0 |
| Best multilingual | `ggml-large-v3-q5_0.bin` | Whisper large-v3 | Q5_0 |

The release is immutable. New model bytes receive a new release tag and a new
catalog revision; existing tags are never overwritten. See `NOTICE.md` for
upstream provenance and licensing.
