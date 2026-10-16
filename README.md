# vztool model distribution

Pinned, unmodified ONNX model files used by [vztool](https://vztool.com). Weights are distributed as GitHub Release assets, not in Git history.

- [BEN2 (mit)](https://github.com/NongfuSpringSweet/vztool-models/releases/tag/BEN2-ONNX-c552aa82688edce09f0ac9d2e31ad53d9d629010), upstream revision `c552aa82688edce09f0ac9d2e31ad53d9d629010`. Original license: [BEN2-LICENSE.txt](BEN2-LICENSE.txt).
- [MODNet (apache-2.0)](https://github.com/NongfuSpringSweet/vztool-models/releases/tag/modnet-webnn-6af52070d14deafc5e55ce6cc4d752a322cdff76), upstream revision `6af52070d14deafc5e55ce6cc4d752a322cdff76`. Original license: [MODNet-LICENSE.txt](MODNet-LICENSE.txt).

Each release includes the original license and model card, upstream provenance and SHA-256 checksums. The original upstream projects and ONNX contributors retain their rights. See models.json for exact sources and file digests. No upstream example images or videos are redistributed.

GitHub Release downloads are accessed through the existing vztool same-origin gateway because browser cross-origin fetch is blocked by GitHub. The application retains its Hugging Face fallback and browser model cache.

Updates are explicit: review the new license and revision, prepare a new release, verify file digests and actual inference/export, then update the application pin. Existing tags and assets are retained; normal website releases do not re-upload unchanged models.
