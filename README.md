# DexDuel voice assets

Versioned, optional HTTPS downloads for DexDuel's offline natural voice. This repository contains voice asset metadata and notices. Application source is maintained separately.

The Natural Voice v1 release contains the exact four files used by DexDuel: its optimized Kokoro-82M ONNX model, af_heart voice, English pronunciation lexicon, and pre-rendered call-outs. The app verifies each file's size and SHA-256 before installation.

Upstream model and voice: https://huggingface.co/hexgrad/Kokoro-82M (Apache-2.0).
ONNX source: https://huggingface.co/onnx-community/Kokoro-82M-v1.0-ONNX (revision 1939ad2a8e416c0acfeecc08a694d14ef25f2231).
Lexicon/rules: https://github.com/hexgrad/misaki (Apache-2.0).
See NOTICE.txt for attribution, modifications, and license texts. No inference server is used; narration runs on the iPad after download.
