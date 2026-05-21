# Evaluation sets

Each `en-{de,ja,ru,zh}/` directory contains:

- `source.txt` — the English source, 300 sentences, one sentence per line, UTF-8.
- `reference.txt` — the professional human translation in the target language.
- `system_1.txt` … `system_4.txt` — outputs from commercial NMT engines and
  open-weight LLMs.
- `README.md` — the source of the data, line counts, and any language-specific notes (setting the BLEU tokenizer to `ja-mecab` for Japanese or `zh` for Chinese; and TER settings for both these languages to `asian_support` and `norm`).

All files are line-aligned: line *N* of every file corresponds to the same segment.

- The source and reference translation data are derived from the Reeve Foundation Multilingual Corpus, used with permission for research and educational purposes only.

## Citing this tutorial

If you use the materials, the evaluation sets, or the analysis pipeline, please cite:

> Balashov, Y. (2026). [*Translation Evaluation Tools for Everyone: A
> Hands-On Tutorial for Freelance Translators and Smaller LSPs.*](https://github.com/YuriBalashov/eamt2026-eval-tutorial)
> Tutorial at the 26th Annual Conference of the European Association for
> Machine Translation (EAMT 2026).

A BibTeX entry is included in `bibliography.bib`.

The evaluation data are derived from the [**Reeve Foundation Multilingual Corpus (RFMC)**](https://github.com/YuriBalashov/reeve-mftc). If you use it in published work, please cite the corresponding papers:

> Balashov, Yuri, Alex Balashov, and Shiho Fukuda Koski. 2025. [Translation Analytics for Freelancers: I. Introduction, Data Preparation, Baseline Evaluations](https://aclanthology.org/2025.mtsummit-1.42/).
> In *Proceedings of Machine Translation Summit XX, Volume 1*, Geneva, Switzerland: European Association for Machine Translation, 538–65

> Balashov, Yuri, Rex VanHorn, Austin Downes, and Mingxi Xu. 2026. Translation Analytics for Freelancers: II. Benchmarking Local LLMs for Confidential Translation Workflows. In *Proceedings of EAMT 2026*, forthcoming.

---

## License

- **Tutorial materials** are licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), for non-commercial/academic use only, with attribution.
- **Evaluation data**: derived from the Reeve Foundation Multilingual Corpus, used with permission for research and educational purposes.
- The MATEO toolkit itself is licensed independently (Apache-2.0); see
  <https://github.com/BramVanroy/mateo-demo>.

