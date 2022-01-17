# Computational Optimal Transport for Machine Learning Reading Group
Over the last few years, optimal transport (OT) has quickly become a central topic in machine learning. 
OT is now routinely used in many areas of ML, ranging from the theoretical use of OT flow for controlling learning algorithms 
to the inference of high-dimensional cell trajectories in genomics. This reading group aims to keep participants up 
to date with the latest research happening in this area.

## Logistics
For Winter 2022 term, meetings will be held weekly on Mondays from 14:00 to 15:00 EST via zoom (for now).

- [Zoom Link](https://umontreal.zoom.us/j/87115614420?pwd=a3dMR3NIeVNwank0TVU0N05DNGkvZz09).
- Password will be provided on slack before every meeting.

- Meetings will be recorded by default. Recordings are available to Mila members [**at this link**](https://drive.google.com/drive/folders/1gOGPrxrC6I6nXVokDymq7RVgYeIRU_dv?usp=sharing). Presenters can email ali.harakeh@mila.quebec to opt out from being recorded.

- **Reading Group participates are expected to read each paper beforehand.**

## Schedule
|   Date   |                         Topic                                               |         Presenters         |        Slides         |
|:--------:|:---------------------------------------------------------------------------:|:--------------------------:|:--------------------------:|
| 01/17/21 | Introduction to Optimal Transport for Machine Learning | Alex Tong <br/>Ali Harakeh | [Part 1](https://drive.google.com/file/d/1yeseuB4Sf48q5GOFyrH0ga4vgvvwxnKD/view?usp=sharing) <br/> [Part 2](https://drive.google.com/file/d/1QFySL-HF-fz9hZCUhbzJydnfKrMsPEKF/view?usp=sharing)|
| 01/24/21 | [Learning with minibatch Wasserstein : asymptotic and gradient properties](http://proceedings.mlr.press/v108/fatras20a.html) |  Kilian Fatras| -- |
| 01/31/21 |                           --                           |             --             | -- |
| 02/7/21  |                           --                           |             --             | -- |
| 02/14/21 |                           --                           |             --             | -- |
| 02/21/21 |                           --                           |             --             | -- |
| 02/28/21 |                           --                           |             --             | -- |

## Paper Presentation Instructions

### Volunteer to Present
- All participants are encouraged to volunteer to present at the reading group. 


- Volunteers can choose a paper from [this](suggested-papers.md) list of suggested papers, or any other paper that is 
related to optimal transport in machine learning. 


- To volunteer, please **send the paper title, link, and your preferred presentation date** the Slack channel 
`#volunteer-to-present` or email `ali.harakeh@mila.quebec`.

### Presentation Instructions
- Presentations should be limited to 40 minutes at most. During the presentation, organizers will act as moderators and 
  will read questions as they come up on the Zoom chat. The aim is to be done in 35-40 min to allow 15 min for general 
  discussion.


- Presentations should roughly adhere to the following outline:
  1. **5-10 minutes**: Problem setup and position to literature.
  2. **10-15 minutes**: Contributions/Novel technical points.
  3. **10-15 minutes**: Weak points, open questions, and future directions.

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
- Ali Harakeh `ali.harakeh@mila.quebec`
- Alex Tong `alexander.tong@mila.quebec`


Modeled after the [Causal Representation Learning Reading Group
](https://github.com/csquires/causal-rep-learning-reading-group).
