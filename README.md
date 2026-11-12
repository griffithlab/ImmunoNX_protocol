# ImmunoNX Protocol

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This repository contains the protocol and supporting materials for the ImmunoNX pipeline, a comprehensive workflow for predicting neoantigens. The manuscript (linked below) describes our computational pipeline (ImmunoNX) and rigorous manual immunogenomics review criteria for designing neoantigen vaccines. We also describe how to run the pipeline for data obtained from a breast cancer cell line (HCC1395), and provide materials from our immunogenomics review of the sequence data and neoantigen candidates identified.

## Manuscript

Link to the manuscript: [arXiv preprint](https://arxiv.org/pdf/2512.08226)

Link to archive of supplementary files: [Zenodo](https://doi.org/10.5281/zenodo.17809276)

## Repository Contents

### Documentation
- **[Preparing_references.md](Preparing_references.md)**: Instructions for preparing the reference bundle required for the pipeline.
- **[RunningPipeline_README.md](RunningPipeline_README.md)**: Step-by-step guide to running the Google Cloud implementation of the ImmunoNX pipeline using WDL workflows and Google Cloud helper scripts.
- **[ManualReview_README.md](ManualReview_README.md)**: Guidelines for quality control checks and manual review of pipeline results to pick neoantigen candidates for a vaccine design (or other downstream experiments).
- **[Troubleshooting_README.md](Troubleshooting_README.md)**: Addresses common issues encountered during pipeline execution and manual review.
- **[Download_ImmunoNX_Example_Data.md](Download_ImmunoNX_Example_Data.md)**: Instructions on how to download the HCC1395 example data we used to run ImmunoNX and the outputs we generated.

### Configuration and Examples
- **[example_yamls/](example_yamls/)**: 
  - `template_immuno_local-WDL.yaml`: Example configuration YAML file for running the pipeline.

### External repositories referenced or used by the pipeline
- [analysis-wdls repository](https://github.com/wustl-oncology/analysis-wdls): The WDL files in this repo contain the necessary instructions for running the ImmunoNX pipeline.
- [cloud-workflows repository](https://github.com/wustl-oncology/cloud-workflows): Contains the Google Cloud helper scripts that enable users to set up their Google Cloud account, storage bucket, and virtual machine (VM) in order to execute the ImmunoNX pipeline.

### License
- **[LICENSE](LICENSE)**: MIT License for this repository.

## Citation

If you use this protocol in your research, please cite our manuscript [arXiv preprint](https://arxiv.org/pdf/2512.08226)

## Contact

For questions or issues, please open an issue on this GitHub repository.
