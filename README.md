# Temporal RL for Energy System Control

The temporal RL agent embeds temporal awareness to RL by integrating forecasts (e.g., load, PV, and wind generation) into decision-making through an attention-based temporal embedding module.
![Temporal RL](https://github.com/user-attachments/assets/d658c1dc-16f2-4958-9237-c7268a6a1f8a)

## Citation
[1] A. H. Ardakani, J. Hurink, I. Gibson and E. Shirazi, *Attention-Based Temporal Reinforcement Learning for Energy System Control*, 2025 IEEE PES Innovative Smart Grid Technologies Conference Europe (ISGT Europe), Valletta, Malta, 2025, pp. 1-5, doi: [10.1109/ISGTEurope64741.2025.11305619](https://doi.org/10.1109/ISGTEurope64741.2025.11305619).

[2] A. H. Ardakani, J. Hurink, I. Gibson and E. Shirazi, *Embedding Temporal Awareness in Reinforcement Learning Models for Energy System Control*, Proceedings of the 16th ACM International Conference on Future and Sustainable Energy Systems (E-Energy '25). Association for Computing Machinery, New York, NY, USA, 2025, 1002–1004. [https://doi.org/10.1145/3679240.3734686](https://doi.org/https://doi.org/10.1145/3679240.3734686)

## Results
![Temporal Embedding](https://github.com/user-attachments/assets/7c0565f3-f8cb-415f-ad64-10bfae5201a6)

## Inference
Run the following notebook:
```
$ 6. attention_TRL.ipynb
```

## Data Sources
| Data | Source |
| --- | --- |
| `PV & Wind Generation` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `Load` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `Electricity Price` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `CO2 Emission` | [Nationaal Energie Dashboard](https://ned.nl) |
