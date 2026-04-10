# Third-Party Model Notices

This repository distributes model artifacts used by VRCAlbum.

The rights and licenses for distributed model artifacts are governed by their respective upstream licenses, not by this repository's own `LICENSE` file.

## Included artifacts

### OpenVision visual encoder

- File: `clip_visual.onnx`
- Derived from: `UCSC-VLAA/openvision-vit-small-patch16-224`
- Upstream: https://github.com/UCSC-VLAA/OpenVision
- Model source: https://huggingface.co/UCSC-VLAA/openvision-vit-small-patch16-224
- Upstream model revision: `0c52da20cbde542fa303ac00070f4c52df5c7bfc`
- Paper: https://arxiv.org/abs/2505.04601
- License: Apache-2.0
- Copyright holder: UCSC-VLAA contributors
- Modification notice: VRCAlbum converted the upstream weights to ONNX FP32 format for desktop inference distribution.

### OpenVision textual encoder

- File: `clip_textual.onnx`
- Derived from: `UCSC-VLAA/openvision-vit-small-patch16-224`
- Upstream: https://github.com/UCSC-VLAA/OpenVision
- Model source: https://huggingface.co/UCSC-VLAA/openvision-vit-small-patch16-224
- Upstream model revision: `0c52da20cbde542fa303ac00070f4c52df5c7bfc`
- Paper: https://arxiv.org/abs/2505.04601
- License: Apache-2.0
- Copyright holder: UCSC-VLAA contributors
- Modification notice: VRCAlbum converted the upstream weights to ONNX FP32 format for desktop inference distribution.

### OpenVision tokenizer

- File: `tokenizer.json`
- Derived from: `UCSC-VLAA/openvision-vit-small-patch16-224`
- Upstream: https://github.com/UCSC-VLAA/OpenVision
- Model source: https://huggingface.co/UCSC-VLAA/openvision-vit-small-patch16-224
- Upstream model revision: `0c52da20cbde542fa303ac00070f4c52df5c7bfc`
- License: Apache-2.0
- Copyright holder: UCSC-VLAA contributors
- Modification notice: This file is redistributed unmodified from the Hugging Face model repository listed above.

### Qwen language model

- File: `Qwen3-0.6B-Q8_0.gguf`
- Source: `Qwen/Qwen3-0.6B-GGUF`
- Model source: https://huggingface.co/Qwen/Qwen3-0.6B-GGUF
- Upstream model revision: `23749fefcc72300e3a2ad315e1317431b06b590a`
- Base model: `Qwen/Qwen3-0.6B`
- Copyright notice: `Copyright 2025 Alibaba Cloud`
- License: Apache-2.0
- Modification notice: This distribution republishes the upstream `Qwen3-0.6B-Q8_0.gguf` artifact without modifying model weights or metadata.

## Redistribution notes

- Redistribution of model artifacts must comply with the applicable upstream licenses and terms.
- This repository does not change or replace the copyright holders of the included models.
- Upstream license texts are included in `third_party/`.
- For OpenVision, refer to the upstream model card, paper, and repository for additional details.
- To satisfy Apache-2.0 derivative-work requirements, this document records the modifications made by VRCAlbum to redistributed artifacts.
- If you need more detail, consult the upstream model card, repository, and license files.
