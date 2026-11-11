# all-mpnet-base-v2, exported to ONNX

A float32 ONNX export of the sentence-embedding model all-mpnet-base-v2, by the
sentence-transformers project (Apache-2.0), fine-tuned from Microsoft's mpnet-base (MIT). The
weights are unchanged in value; only the format changed. The tokenizer files are unchanged.

Not affiliated with or endorsed by the sentence-transformers authors, Hugging Face or Microsoft.

## Download

`onnx.tar.gz` from the release, checked against `onnx.tar.gz.sha256`.

## Credits

All of the model's work is theirs; this repository only changes its file format.

- **all-mpnet-base-v2**: the sentence-transformers project, created by Nils Reimers and Iryna
  Gurevych and maintained by Tom Aarsen at Hugging Face. The model was developed during Hugging
  Face's Community Week using JAX/Flax for NLP & CV, on 7 TPU v3-8, with guidance from members
  of Google's Flax, JAX and Cloud teams. It was trained on over one billion sentence pairs drawn
  from public datasets, whose authors made them available.
- **mpnet-base**: Kaitao Song, Xu Tan, Tao Qin, Jianfeng Lu and Tie-Yan Liu, Microsoft.

If you use this model in your work, please cite the papers its authors ask to be cited:

```bibtex
@inproceedings{reimers-2019-sentence-bert,
  title     = {Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks},
  author    = {Reimers, Nils and Gurevych, Iryna},
  booktitle = {Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing},
  year      = {2019},
  note      = {arXiv:1908.10084}
}

@article{song2020mpnet,
  title   = {MPNet: Masked and Permuted Pre-training for Language Understanding},
  author  = {Song, Kaitao and Tan, Xu and Qin, Tao and Lu, Jianfeng and Liu, Tie-Yan},
  journal = {arXiv preprint arXiv:2004.09297},
  year    = {2020}
}
```

## Licences

- `LICENSE` - Apache License 2.0, for the model and this repository.
- `LICENSE-MPNet` - MIT, for microsoft/mpnet-base, with Microsoft's copyright.
- The archive carries its own `LICENSE` and `NOTICE`.
