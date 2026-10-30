# matlab-hackathon-energy
Random Forest + Gradient Boosting

A machine learning model that predicts building site energy use intensity (Site EUI) from weather and building characteristics. Accurate predictions help organisations find high-use buildings to retrofit and cut energy waste.

## Contents
| File | Description |
|---|---|
| `train.csv` | Training data |
| `test.csv` | Test data |
| `Hackathon Briefing Slides.pdf` | Hackathon brief |
| `siteEuiModel.mat` | Trained MATLAB model, not stored in the repo (see below) |

## Trained model
`siteEuiModel.mat` is ~200 MB, over GitHub's 100 MB file limit, so it is not committed. Download it from this repo's Releases page and place it in the project folder, then:

```matlab
load siteEuiModel.mat
% predictions = predict(<modelVariable>, testTable);
```
