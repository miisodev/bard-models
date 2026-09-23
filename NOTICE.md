# Model asset provenance and notices

The Bard model releases contain exact Q6_K GGUF conversions downloaded from
these public, pinned Hugging Face conversion repositories:

- `handy-computer/whisper-small-gguf` at
  `a2073177cb69bd74b9ca9460b852d17fbfd5d68c`
- `handy-computer/parakeet-tdt-0.6b-v2-gguf` at
  `382796e405a9fe37145938dccbabfb25e93e4286`
- `handy-computer/Qwen3-ASR-1.7B-gguf` at
  `3555bd238a8572bbace3ebf60d23b036dc0a5dbe`

The application records the exact asset SHA-256 and byte size. The files are
rehosted unchanged for Bard's first-party download path; Bard does not modify
or claim ownership of the weights.

## Licences

- **Whisper Small:** Apache-2.0 conversion card; base model
  <https://huggingface.co/openai/whisper-small>. Retain the applicable Apache
  notice and attribution.
- **Parakeet TDT 0.6B v2:** CC-BY-4.0; base model
  <https://huggingface.co/nvidia/parakeet-tdt-0.6b-v2>. Attribution and the
  licence notice must accompany redistribution and use.
- **Qwen3-ASR 1.7B:** Apache-2.0 conversion card; base model
  <https://huggingface.co/Qwen/Qwen3-ASR-1.7B>. Retain the applicable Apache
  notice and attribution.

Conversion and engine references:

- <https://huggingface.co/handy-computer/whisper-small-gguf>
- <https://huggingface.co/handy-computer/parakeet-tdt-0.6b-v2-gguf>
- <https://huggingface.co/handy-computer/Qwen3-ASR-1.7B-gguf>
- <https://github.com/handy-computer/transcribe.cpp/tree/v0.2.3>
