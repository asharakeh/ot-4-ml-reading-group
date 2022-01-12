# Computational Optimal Transport for Machine Learning Reading Group
Over the last few years, optimal transport (OT) has quickly become a central topic in machine learning. 
OT is now routinely used in many areas of ML, ranging from the theoretical use of OT flow for controlling learning algorithms 
to the inference of high-dimensional cell trajectories in genomics. This reading group aims to keep participants up 
to date with the latest research happening in this area.

## Reading Group
For Winter 2022 term, meetings will be held weekly on Mondays from 14:00 to 15:00 EST via zoom.

### Logistics
- [Zoom Link](https://umontreal.zoom.us/j/87115614420?pwd=a3dMR3NIeVNwank0TVU0N05DNGkvZz09).
- Password will be provided on slack before every meeting.
- Meetings will be recorded by default. **Presenters can send an email to ali.harakeh@mila.quebec to opt out from being recorded.**

### Schedule
|   Date   |                         Topic                          |         Presenters         |
|:--------:|:------------------------------------------------------:|:--------------------------:|
| 01/17/21 | Introduction to Optimal Transport for Machine Learning | Alex Tong <br/>Ali Harakeh |
| 01/24/21 |                           --                           |             --             |
| 01/31/21 |                           --                           |             --             |
| 02/7/21  |                           --                           |             --             |
| 02/14/21 |                           --                           |             --             |
| 02/21/21 |                           --                           |             --             |
| 02/28/21 |                           --                           |             --             |

## Suggested Papers
TBD

## Useful References
This is a list of useful references including code, text books, and presentations.

### Code
- [POT: Python Optimal Transport](https://pythonot.github.io/): This open source Python library provide several 
   solvers for optimization problems related to Optimal Transport for signal, image processing and machine learning. 
   **This library has the most efficient exact OT solvers.**
- [GeomLoss](https://www.kernel-operations.io/geomloss/): The GeomLoss library provides efficient GPU 
   implementations for Kernel norms, Hausdorff divergences, and Debiased Sinkhorn divergences. **This library has 
   the most scalable duel OT solvers embedded within the Sinkhorn divergence computation.**

### Textbooks
- [Computational Optimal Transport](https://arxiv.org/abs/1803.00567)

```
@article{peyre2019computational,
  title={Computational optimal transport: With applications to data science},
  author={Peyr{\'e}, Gabriel and Cuturi, Marco and others},
  journal={Foundations and Trends{\textregistered} in Machine Learning},
  volume={11},
  number={5-6},
  pages={355--607},
  year={2019},
  publisher={Now Publishers, Inc.}}
```

### Workshops and Presentations
- [NeurIPS 2021 Workshop on Optimal Transport and Machine Learning](https://otml2021.github.io/)

## Organizers
- Ali Harakeh (ali.harakeh@mila.quebec)
- Alex Tong (alexander.tong@mila.quebec)
