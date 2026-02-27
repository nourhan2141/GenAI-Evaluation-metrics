# Mini Report — Model A vs Model B (Image Generation)

## Setup

- Metrics: CLIPScore, FID, Inception Score (IS), Human ratings

## Results

| Metric              |    Model A |    Model B |
|:--------------------|-----------:|-----------:|
| Avg CLIPScore (↑)   |   0.336664 |   0.328465 |
| FID vs Real (↓)     | 191.788    | 211.832    |
| Inception Score (↑) |   5.8775   |   6.1471   |


## Interpretation

- Higher **CLIPScore** = Better prompt alignment.

- Lower **FID** = More realism + diversity vs real images.

- Higher **Inception Score (IS)** = Better image quality and diversity.
