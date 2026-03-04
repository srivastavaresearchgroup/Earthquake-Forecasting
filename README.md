# b-Value-Driven Deep Learning for Earthquake Forecasting

This repository contains the code and data associated with two companion papers on 
spatiotemporal b-value analysis and deep learning-based earthquake forecasting in 
the Japanese subduction zone.

## Papers

**Paper 1 — Methodology**  
*Detecting Spatiotemporal b-Value Anomalies with a Progressive Deep Learning Architecture*  
Jonas Köhler, Wei Li, Johannes Faber, Georg Rümpker, Nishtha Srivastava  
[arXiv:2602.12408](https://arxiv.org/abs/2602.12408)  
[![DOI](https://zenodo.org/records/15323730)](https:doi.org/10.5281/zenodo.10829448)

**Paper 2 — Application**  
*Probabilistic and Alarm-Based Evaluation of a b-Value-Driven Deep Learning Earthquake Forecast*  
Jonas Köhler, Wei Li, Johannes Faber, Georg Rümpker, Nishtha Srivastava  
[arXiv:2603.03079](https://arxiv.org/abs/2603.03079)

## Repository Structure
```
├── methodology/   # Code for Paper 1: model architecture and b-value framework
├── application/   # Code for Paper 2: forecast evaluation and skill scores
└── README.md
```

## Requirements

Requirements and installation for those requirements are given in `00_Download_ISC.ipynb_`

## Usage

The code in methodolody can be used as is - create the masterdirectory required at the top of each notebook, the subdirectories and then execute them in numerical order.

The code for the application requires the data and models created by the methodolody. As the data block is quite large, it is not provided here, but can be calculated using notebooks the Download-ISC and Preprocessing Notebooks.

A model history and an Autoencoder are provided in application/, they have to be put in the folder structure again.


## Citation

If you use this code, please cite the relevant paper(s):
```bibtex
@article{kohler2026detecting,
  title={Detecting Spatiotemporal b-Value Anomalies with a Progressive Deep Learning Architecture},
  author={Köhler, Jonas and Li, Wei and Faber, Johannes and Rümpker, Georg and Srivastava, Nishtha},
  journal={arXiv preprint arXiv:2602.12408},
  year={2026}
}

@article{kohler2026probabilistic,
  title={Probabilistic and Alarm-Based Evaluation of a b-Value-Driven Deep Learning Earthquake Forecast},
  author={Köhler, Jonas and Li, Wei and Faber, Johannes and Rümpker, Georg and Srivastava, Nishtha},
  journal={arXiv preprint arXiv:2603.03079},
  year={2026}
}
```
