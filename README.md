# Bard model host

First-party binary releases for the models curated by Bard.

These files are redistributed from the upstream projects and conversion revisions
named in each release's manifest. The application catalog records the model
role, architecture, source revision, licence, byte size, and SHA-256 for every
asset. Bard's source code does not imply ownership of third-party model weights.

## Release contents

| Bard role | Asset | Source conversion | Quantization |
| --- | --- | --- | --- |
| Fast multilingual | `whisper-small-Q6_K.gguf` | Whisper Small | Q6_K |
| Best English | `parakeet-tdt-0.6b-v2-Q6_K.gguf` | Parakeet TDT 0.6B v2 | Q6_K |
| Best multilingual | `Qwen3-ASR-1.7B-Q6_K.gguf` | Qwen3-ASR 1.7B | Q6_K |

The release is immutable. New model bytes receive a new release tag and a new
catalog revision; existing tags are never overwritten. See `NOTICE.md` for
upstream provenance and licensing, and `model-manifest.json` for exact hashes.
