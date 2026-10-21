# Activity Cards models

On-device models used by the Activity Cards app. Files are published as
**release assets**; the repository itself only holds licensing information.

| Release | Model | Use |
|---|---|---|
| `story-lfm2.5-1.2b-B-v1` | LFM2.5-1.2B-Instruct fine-tuned for social stories, ONNX Runtime GenAI int4 (CPU) | AI social stories (short prompt + JSON schema guidance) |

Each release has a `manifest.json` listing every file with its size and
SHA-256; the app downloads the files and checks them against it.

## License

The models are modified versions of Liquid AI's LFM2.5 models and are
distributed under the **LFM Open License v1.0** (`LICENSE-LFM`). See `NOTICE`
for the base model and the changes made. Commercial use is licensed only while
the licensee's annual revenue is below the threshold set in that license
(USD 10,000,000).
