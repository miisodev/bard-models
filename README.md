# Bard models

The speech-model files that [Bard: Clipboard, Draw and Dictate](https://github.com/miisodev/bard) downloads for on-device dictation.

[**Bard**](https://github.com/miisodev/bard) · [Download Bard](https://miiso.dev/bard) · [Releases](https://github.com/miisodev/bard-models/releases) · [Notices](./NOTICE.md)

These files are open-weight models from their upstream projects, converted to GGUF and rehosted unchanged so that Bard downloads from one place it controls. Bard's catalogue pins each file by its release URL, byte size and SHA-256, and a download is hashed and loaded before it is ever used. Hosting them here does not make Bard the owner of the weights.

## Release contents

| Bard role | Asset | Upstream model | Quantisation | Release |
| --- | --- | --- | --- | --- |
| Fast | `parakeet-tdt-0.6b-v3-Q6_K.gguf` | [Parakeet TDT 0.6B v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3) (CC-BY-4.0) | Q6_K | [models-v3](https://github.com/miisodev/bard-models/releases/tag/models-v3) |
| General | `Qwen3-ASR-1.7B-Q6_K.gguf` | [Qwen3-ASR 1.7B](https://huggingface.co/Qwen/Qwen3-ASR-1.7B) (Apache-2.0) | Q6_K | [models-v2](https://github.com/miisodev/bard-models/releases/tag/models-v2) |

Whisper Small and Parakeet TDT 0.6B v2 are retired from the catalogue; their assets remain in the `models-v2` release for rollback.

Every release is immutable. New model bytes get a new release tag and a new catalogue revision in Bard; existing tags are never overwritten. [`model-manifest.json`](./model-manifest.json) carries the exact hashes, and [`NOTICE.md`](./NOTICE.md) the upstream provenance and licences.

## Where things live

- **Bard's source and its model catalogue:** [miisodev/bard](https://github.com/miisodev/bard), in `src-tauri/src/catalog/catalog.json`
- **Bard's installers and packages:** [miisodev/bard-releases](https://github.com/miisodev/bard-releases)
- **Product page:** [miiso.dev/bard](https://miiso.dev/bard)

## License

This repository's own files are [MIT](./LICENSE). Each model keeps its upstream licence, in [`LICENSES/`](./LICENSES): CC-BY-4.0 for Parakeet, Apache-2.0 for Qwen3-ASR, and MIT (© OpenAI) for Whisper.
