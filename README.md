# Diploma Thesis

LaTeX source for the diploma thesis.

## Topic

This diploma thesis studies federated anomaly detection for cybersecurity in
5G/6G network environments. It focuses on log-based anomaly detection using a
pretrained BERT model adapted with LoRA, and evaluates federated training across
multiple clients with different data distributions and aggregation strategies.

## Build

Run from the project root:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir=build main.tex
```

The generated PDF is written to:

```text
build/main.pdf
```

## Code Repositories

- [hdfs_anomaly_detection](https://github.com/kontogiannisvangelis/hdfs_anomaly_detection)
- [flower_hdfs_anomaly_detection](https://github.com/kontogiannisvangelis/flower_hdfs_anomaly_detection)

## Notes

- `main.tex` contains the thesis metadata and includes the chapter files.
- The `build/` directory contains generated LaTeX artifacts and is ignored by Git.
- The `noindex` template option disables index generation.
